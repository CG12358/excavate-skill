# Interrogation Axes

Six axes of intent. Track confidence on each internally throughout the conversation. Do not show scores to the user unless asked. Proceed to Phase 2 only when all six are at sufficient confidence.

Sufficient confidence does not mean perfect information — it means you have enough to make a decision that is specific to this project rather than defaulting to the general category.

---

## Axis 1 — Feeling

**What you're measuring:** The visceral experience of being inside the product, not the look of it from the outside. Not aesthetics. Physicality.

**Why it matters:** This axis determines energy, density, pacing, and the emotional register the surface operates in. "Clean" and "modern" are not feelings. "Like opening a blueprint in a drafting room" is a feeling.

**Question bank** (draw 1–2 per round, never all):
- If you stepped inside this product the way you step into a room — what kind of room would it be?
- What should someone feel thirty seconds after landing on this for the first time?
- Is this a tool someone uses with focus and quiet, or with energy and speed?
- What's one word you'd use that isn't "clean", "modern", "minimal", or "bold"?
- What does it feel like when it's working exactly right?

**Confidence signals:**
- Low: user gives aesthetic adjectives ("clean", "modern", "sleek")
- Medium: user gives a comparison with a specific emotional note ("like Linear but less cold")
- High: user gives a scene, a texture, a physical analog, or a use-state feeling

---

## Axis 2 — Anti-Target

**What you're measuring:** What the user would reject immediately on first contact. What would make them close the tab, distrust it, or feel like it wasn't built for them.

**Why it matters:** Rejection signals are more diagnostic than positive signals. They define the boundaries of the space you're building inside. One anti-target is worth three positive descriptors.

**Question bank:**
- You open the finished product and immediately close it. What did you see?
- What's a product in this space that looks polished but feels wrong to you — and what specifically feels wrong about it?
- What visual treatment would make this feel like it wasn't built for you?
- If this ended up looking like a template, what would give that away?
- What would make this feel dishonest or performative?

**Confidence signals:**
- Low: "I don't want it to look cheap" (non-specific)
- Medium: "I don't want it to look like a Webflow template" (category-specific)
- High: "I don't want rounded corners everywhere and a purple gradient — it needs to feel like something built by engineers, not marketed at them" (specific enough to generate a refuse list)

---

## Axis 3 — Scene

**What you're measuring:** The physical and emotional context of use. Who is actually using this, where they are, what they're doing before and after, and what light they're in.

**Why it matters:** Scene determines dark/light mode before any aesthetic consideration does. It determines density (a dashboard used in 30-second bursts needs different information density than one used in 2-hour sessions). It determines the emotional register of the copy.

**Question bank:**
- Walk me through the moment someone opens this. What were they doing five minutes ago?
- Where are they physically when they use this — office, home, on the move?
- Are they using it alone, or with someone else watching?
- How much time do they have? Is this a quick check or a long session?
- What do they need to feel before they close it?

**Confidence signals:**
- Low: "users" or "people who need X"
- Medium: a role + context ("developers at SaaS companies, usually in the evening")
- High: a specific moment + emotional state ("ops leads who just got paged at 11pm and need to understand what's wrong in under 60 seconds")

---

## Axis 4 — Edge Audience

**What you're measuring:** The person this is not built for. The user who, if they ended up using it, would signal that something went wrong in the positioning or the design.

**Why it matters:** The wrong audience for a product is usually the same as the generic audience for its category. Naming the edge audience helps resist the pull toward defaults that are "for everyone" and therefore for no one.

**Question bank:**
- Who's the last person you'd want using this?
- If someone who wasn't your intended user picked this up, what would confuse or repel them about it?
- Is there a type of user who would misread what this tool is for?
- Who would look at this and think it's "not for them" — and is that the right reaction?

**Confidence signals:**
- Low: "I want everyone to be able to use it"
- Medium: "probably not enterprise teams, more indie developers"
- High: "if a growth marketer at a 500-person company opened this and felt at home, something went wrong"

---

## Axis 5 — Reference Delta

**What you're measuring:** The thing that's closest to what they have in mind, and — critically — what they would change about it.

**Why it matters:** The delta (what they'd change) is the actual design brief hiding inside a reference. The reference itself is just a category signal. You want the gap.

**Question bank:**
- What's one product, site, or UI that comes closest to the feeling you're going for?
- If you had that thing in front of you and could change three things, what would they be?
- What does that reference get right that everything else in this space gets wrong?
- Is there something from a completely different industry that feels closer to what you want than anything in your own category?

**Confidence signals:**
- Low: no reference offered, or reference is very generic ("I like Apple's style")
- Medium: specific reference with a general direction ("like Vercel's dashboard but warmer")
- High: specific reference with a specific delta ("like Vercel's dashboard but I'd remove the card containers, make the type bigger, and get rid of the dark mode default — it should work in a bright office")

---

## Axis 6 — Constraint

**What you're measuring:** What cannot change. What must not be touched. The hard edges of the design space.

**Why it matters:** Without knowing constraints, a coding agent will invent its own. Constraints also reveal what the user actually cares about most — the things they name as untouchable are usually the things that carry the product's identity.

**Question bank:**
- Is there anything that already exists — a brand element, a color, a logo, a typeface — that must stay exactly as it is?
- Are there any platform, performance, or accessibility requirements that are non-negotiable?
- Is there anything the previous version got right that can't be lost?
- Are there elements of this that you consider already decided and don't want to re-litigate?
- What would you never forgive a coding agent for changing without asking?

**Confidence signals:**
- Low: "nothing specific" with no follow-up
- Medium: a brand color or existing component that must stay
- High: a specific list of untouchable elements with reasons

---

## Axis Priority

Ask in this priority order when in doubt:
1. Anti-target (most diagnostic)
2. Scene (unlocks dark/light, density, copy register)
3. Feeling (shapes energy and texture)
4. Reference delta (surfaces the hidden brief)
5. Constraint (locks the edges)
6. Edge audience (confirms positioning is intentional)

Reorder based on what the user's initial message has already resolved. If they led with a constraint, move it to resolved and prioritize what's missing.
