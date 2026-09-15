# Brief Format

This is the output template. Fill it when all 6 axes are resolved and the reflection round is confirmed. Present it in full. Do not summarize it. Do not add sections not listed here.

Every field must be specific to this project. A field that could be copied and pasted into a brief for a different product in the same category is not finished.

---

```
╔══════════════════════════════════════════════════════════════════╗
║  EXCAVATE BRIEF                                                  ║
║  [Project name or working title]                                 ║
║  [Date]                                                          ║
╚══════════════════════════════════════════════════════════════════╝

─── FEELING ─────────────────────────────────────────────────────────
3 words. Visceral, not aesthetic. Not "clean", "modern", "bold", or
any adjective that describes how it looks. Name what it feels like
to be inside it.

[WORD] · [WORD] · [WORD]

Expanded (1–2 sentences):
[What does the user experience in the first 30 seconds that no other
product in this category delivers?]

─── ANTI-TARGETS ────────────────────────────────────────────────────
What would make the user close the tab, distrust the product, or
feel it wasn't built for them. These are as important as the targets.

- [Specific visual or UX treatment to reject, with reason]
- [...]
- [...]

─── SCENE ───────────────────────────────────────────────────────────
Who:     [A specific person, not "users" or "developers" or "teams"]
Where:   [Physical or digital context — desk, phone, second monitor,
          outdoors, in a meeting, on the go]
When:    [The moment of use and what preceded it emotionally]
Light:   [The ambient environment — this determines dark/light mode
          as a physical decision before any aesthetic one]
Session: [Quick check-in or extended session? How long, how often?]

─── EDGE AUDIENCE ───────────────────────────────────────────────────
Who would feel at home with this product that shouldn't — and what
design choices would attract them?

[One sentence on who the wrong user is and why this brief steers away
from the decisions that would make them feel at home.]

─── REFUSE LIST ─────────────────────────────────────────────────────
Specific patterns banned for this project. These are not general
best practices — they are defaults that would pull this brief toward
a generic output.

- [Pattern name]: [Why it's wrong for this specific brief]
- [...]
- [...]

─── CONTENT TRUTH ───────────────────────────────────────────────────
Real — use as-is, do not invent or modify:
- [Existing brand elements, copy, data, assets that must be used]

Authorable — design at full fidelity, label synthetic:
- [Content that doesn't exist yet and can be invented for the design,
  labeled clearly so the client knows to replace it]

Off-limits to claim:
- [Commercial claims, benchmarks, customer logos, or capabilities
  not confirmed by the user]

─── THESIS ──────────────────────────────────────────────────────────
One sentence. What this surface owns that nothing else in its
category does. What it refuses to be.

[Single sentence.]

The category default this brief refuses:
[What a coding agent would build if given only the product type and
no brief — name it specifically so it cannot happen by accident.]

─── CONSTRAINTS ─────────────────────────────────────────────────────
Must not change:
- [Brand elements, existing components, design decisions already made]

Platform & delivery:
- [Framework, performance targets, browser support, screen sizes,
  accessibility requirements]

Open decisions (for the coding agent to resolve):
- [Choices that excavate did not resolve because the user left them
  open — name them explicitly so the agent knows to ask rather than
  assume]

─── HANDOFF ─────────────────────────────────────────────────────────
To the coding agent:

1. Read this brief in full before making any visual decision.
2. The THESIS is the direction contract. If a visual choice doesn't
   serve the thesis, it doesn't belong in the build.
3. The REFUSE LIST overrides category defaults for this project.
4. The FEELING section is not decoration — it is the test for every
   design decision. Ask: does this choice produce that feeling?
5. The SCENE section determines dark/light mode and information
   density. Do not override it with aesthetic preference.
6. Open decisions in CONSTRAINTS are yours to resolve — but resolve
   them explicitly, not silently.

╔══════════════════════════════════════════════════════════════════╗
║  STATUS: PENDING USER APPROVAL                                   ║
╚══════════════════════════════════════════════════════════════════╝
```

---

## Field completion guidance

**FEELING — 3 words:** These cannot be design adjectives. Test: would a non-designer understand what they mean without seeing the product? "Surgical · Immediate · Honest" passes. "Clean · Modern · Bold" fails.

**ANTI-TARGETS:** Minimum two, maximum five. Each must be specific enough that a coding agent could use it as a test. "Don't make it look like a template" fails. "No 24px border-radius on everything, no purple-to-blue gradient, no three-column icon grid" passes.

**SCENE — Light field:** This is not a vibe. It determines a real decision. "Office fluorescents" → probably light mode, or a carefully considered dark that reads in bright ambient light. "Late night, one monitor" → dark mode is genuinely better here. "Outdoors, mobile" → high contrast, no subtlety in color choices. Write the environment, let the coding agent derive the implications.

**REFUSE LIST:** Pull from `reference/anti-defaults.md` filtered for relevance to this specific brief. Do not copy the entire list. A refuse list of 20 items is noise. 3–6 targeted items is a brief.

**THESIS — Category default line:** This is the brief's most important safety mechanism. Name exactly what a coding agent would build without this brief. "Without this brief, a coding agent would produce a dark dashboard with a sidebar nav, metric cards, and a purple accent." That sentence makes the brief's job visible and makes it impossible to ignore.

**CONSTRAINTS — Open decisions:** Be honest about what excavate did not resolve. An open decision left unnamed becomes an assumption. Name it: "The user did not specify a framework. The coding agent should confirm before starting." This is not a failure of the brief — it is the brief being responsible.
