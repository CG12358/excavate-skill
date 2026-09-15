# Excavate

A design interrogation skill. It refuses to generate until it understands. Ask it what to build, answer its questions, and it produces a locked design brief you can hand to any coding agent.

---

## The problem it solves

When you describe a UI to an AI, it fills every gap in your description with the most common pattern from its training data. You said "dashboard" and it heard "sidebar nav + metric cards + purple accent". You said "landing page" and it built a hero section, a three-column feature grid, and a pill CTA button.

Excavate holds that generation gate closed. It interrogates your intent across six axes — feeling, anti-targets, scene, edge audience, reference delta, and constraints — until it has enough signal to produce a brief that's specific to your product, not your category.

The brief is the output. Code is someone else's job.

---

## How to use it

**Trigger:** Mention `excavate` or ask it to run the excavate skill before describing your project.

**Then:**
1. Describe what you're building — as much or as little as you know
2. Answer questions in batches of 2–3
3. Confirm the reflection round (the AI mirrors back what it understood — correct anything wrong)
4. Receive the locked brief
5. Approve it
6. Hand it to your coding agent with the instruction: *"Read this brief in full before making any visual decisions."*

**How many rounds of questions?** Depends on how much your initial description resolved. A vague prompt usually takes 2–3 rounds. A specific prompt sometimes takes 1. Excavate will tell you what's still unresolved if you want to know.

---

## What it asks about

Six axes, in rough priority order:

- **Anti-target** — What would make you close the tab immediately?
- **Scene** — Who's using this, where, under what light?
- **Feeling** — What does it feel like to be inside it (not look at it)?
- **Reference delta** — What existing thing is closest, and what would you change?
- **Constraint** — What cannot move?
- **Edge audience** — Who's the wrong user for this?

---

## What it produces

A locked brief with these sections:

| Section | What it contains |
|---|---|
| FEELING | 3 words (visceral, not aesthetic) + 1–2 sentence expansion |
| ANTI-TARGETS | Specific things to reject, with reasons |
| SCENE | Who, where, when, under what light, session length |
| EDGE AUDIENCE | The wrong user and the design choices that would attract them |
| REFUSE LIST | Category defaults banned for this specific project |
| CONTENT TRUTH | What's real vs. authorable vs. off-limits to claim |
| THESIS | One sentence: what this surface owns and what it refuses to be |
| CONSTRAINTS | Untouchables, platform/delivery requirements, open decisions |
| HANDOFF | Instructions for the coding agent |

---

## Installing

Drop the `excavate-skill` folder into your agent's skills directory:

```
# For Antigravity / AGY
~/.gemini/config/skills/excavate-skill/

# For project-local use
.agents/skills/excavate-skill/
```

Most agent harnesses that support skill loading will pick it up from either location.

---

## What it doesn't do

- **Does not write code.** That's the coding agent's job, after the brief.
- **Does not suggest fonts, colors, or layouts** during interrogation. That's the brief's job.
- **Does not generate mockups or wireframes.** The brief is the output. Visuals come after.
- **Does not cover print, spatial, or branding design** in v1. Web/UI only. Design-general is planned for v2.

---

## License

MIT License + Commons Clause

Free to use, fork, and extend. You may not sell excavate or a product whose primary value is excavate. Attribution required.

See [LICENSE](./LICENSE) for full terms.

---

## Contributing

Open an issue before opening a PR. The anti-defaults list in `reference/anti-defaults.md` is the most useful thing to contribute to — if you've spotted a default pattern that isn't there, name it precisely and explain what it signals.

The skill is written as plain markdown instructions, not code. Contributions that add scripts, tools, or automation are welcome but must be covered under the same MIT + Commons Clause terms.

---

## Roadmap

- v1.0 — Web/UI design (this release)
- v2.0 — Design-general: branding, print, spatial, product
