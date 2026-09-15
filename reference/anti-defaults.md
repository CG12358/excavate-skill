# Anti-Defaults

This is the pattern-recognition layer. Load it before asking questions. Know these before the conversation starts.

These are not bans. They are defaults — things an AI reaches for when the design space is underspecified. The goal is not to prohibit them but to ensure they were chosen, not assumed. If a brief explicitly calls for one, use it fully. If a brief doesn't call for it, don't reach for it.

When a user's answers drift toward one of these, don't name the ban. Ask a question that opens a different direction.

---

## Structural Defaults

**The SaaS skeleton.** Hero section with headline + subhead + one CTA button → 3-column feature grid with icons → social proof band → second CTA. This structure exists in the majority of AI-generated landing pages. It is not wrong. It is invisible. A product that uses it is legible but not memorable.

**The dashboard default.** Sidebar nav (icon + label, collapsed on mobile) → top bar with avatar + notifications → content area filled with metric cards. This is the mental model every coding agent defaults to for "dashboard". It is often correct. It is never distinctive.

**The nested card problem.** Cards inside cards. A card component used as the default container for everything — sections, stats, list items, modals — regardless of whether containment adds meaning. Card radii and shadows become the visual noise floor.

**The modal reflex.** Triggering a modal for any action that requires more than one input, regardless of whether interruption or focus protection is actually needed. Modals used as a substitute for thinking about where the action belongs in the flow.

**Section enumeration.** 01 / 02 / 03 labels on landing page sections. These communicate sequence when sequence carries no information the reader needs. They are decoration wearing the costume of structure.

**The eyebrow / kicker.** A small uppercase label above a heading ("FEATURES", "WHY US", "FOR DEVELOPERS"). The heading should speak for itself. The label signals that it can't.

---

## Visual Defaults

**The modern minimal trap.** Stark white background. One thin-weight sans-serif. Generous whitespace. A single small-saturated accent color. This reads as intentional design. It is the absence of design decisions. Every default browser stylesheet with one CSS variable changed lands here.

**The "premium dark" assumption.** Dark mode chosen because it signals quality, sophistication, or technical credibility — not because the use scene demands it. Dark mode for a tool used in a bright office under fluorescent lights is a costume. Dark mode chosen from the user's physical environment is a decision.

**The developer-tool costume.** Near-black or very dark neutral background. One high-saturation neon accent (green, cyan, or orange). Monospace type used decoratively for non-code content. This look signals "serious technical tool" without the underlying product needing to be one.

**The AI-product gradient.** Purple-to-blue or indigo-to-violet gradient used as the primary brand expression. This is the visual shorthand for "AI product" in the same way that a stethoscope icon means "health app". It communicates category, not identity.

**The warm editorial default.** Warm cream or off-white ground. High-contrast serif display face. Terracotta, signal red, or dusty rose accent. This cluster appears whenever an AI is told to make something feel "human", "warm", "thoughtful", or "editorial". The cluster is coherent. It is also what every other AI produces under those prompts.

**The neon-on-void cluster.** Very dark or pure-black background. One oversaturated accent, often with a glow or radial blur behind it. This is the aesthetic of crypto landing pages, gaming dashboards, and AI startups that want to feel like science fiction. It signals urgency and edge. It has become its own genre default.

---

## Typography Defaults

**Training-data display faces.** Fonts that appear at high frequency in AI-generated web work because they dominated the design discourse when training data was collected: Fraunces, Playfair Display, Cormorant, Syne, Space Grotesk, Space Mono, DM Sans, DM Serif, Plus Jakarta Sans, Outfit, Instrument Sans, Inter used as a display face. These are not bad fonts. They are overrepresented. Using one without a specific reason is a signal that the AI chose rather than the designer.

**Tracking abuse.** Letter-spacing pushed beyond -0.04em on display text. Wide positive tracking on body text. These are applied as aesthetic gestures rather than calibrated typographic decisions.

**The weight collapse.** Using only Regular and Bold across the entire type system. Weight contrast is one of the most expressive tools in a type system. Collapsing it to two stops produces a flat hierarchy.

**Monospace as costume.** Monospace type applied to non-code content because the product is "technical" or "data-driven". Monospace signals code and measurement. When it signals neither, it signals that someone thought it looked technical.

---

## Component Defaults

**The roundness tax.** Border radius applied uniformly and generously to everything (20px, 24px, or higher) because it "feels friendly" or "modern". Roundness is a design decision. When applied without calibration to the content and context, it reads as a template default, not a design system.

**The pill CTA button.** Full border-radius button (pill shape) in the brand's most saturated color, full-width on mobile, often with a trailing chevron or arrow icon. This is the default primary action affordance in approximately every AI-generated interface. It is not wrong. It is invisible.

**The ghost button pair.** A solid primary button next to an outlined or ghost secondary button. This pairing is so common it has become the default affordance for "one important action, one less important action". It reads correctly. It reads generically.

**The icon system gap.** Mixing icon libraries (Heroicons, Lucide, Phosphor, Tabler) across a single interface because they look "similar enough". They are not. Stroke weight, corner treatment, and optical size differ between libraries. The visual noise is subtle but cumulative.

**The skeleton loader everywhere.** Skeleton loading states applied to every element regardless of whether the content actually has a meaningful load delay. Skeletons as a default rather than as a considered response to a real load experience.

**The avatar ring.** A circular cropped photo inside a ring (usually in brand color or white with a shadow) as the default user representation. This is the UI component equivalent of a stock photo. It communicates "user" without communicating anything specific.

---

## Motion Defaults

**Scroll animation inflation.** Every section fades up and slides in on scroll, staggered by 100–200ms per element. Applied uniformly across the entire page. This was expressive the first time it was used. It is now invisible — and when every element moves, no element has emphasis.

**The hover scale.** `transform: scale(1.03)` or `scale(1.05)` applied on hover to interactive cards. It communicates interactivity. It does not communicate anything about what the interaction does or means.

**The entrance bounce.** `cubic-bezier` easing with a slight overshoot applied to modals, drawers, tooltips, and popovers. Bouncy easing was borrowed from native mobile conventions. On the web, it reads as playful by default — regardless of whether the product's context calls for playfulness.

**The submit celebration.** Confetti, checkmark animation, emoji burst, or other "delight" animation on form submission — regardless of the emotional register of what was just submitted. Submitting a medical form and ordering a pizza do not call for the same celebration.

**The loading spinner monoculture.** A circular spinner as the only loading state in the system. No skeleton, no progress indication, no partial content reveal. The spinner communicates "waiting" without communicating anything about what or how long.

---

## Copy Defaults

**The rhetorical question headline.** "Tired of [pain point]?" / "What if [your tool] was actually easy?" This pattern assumes the reader's frustration, names it, and positions the product as relief. It works. It is also the headline pattern in the majority of SaaS landing pages.

**The benefit-verb bullet.** Feature lists that begin with verbs: "Boost productivity." "Save time." "Scale effortlessly." "Collaborate seamlessly." These bullets are interchangeable across products. They communicate that the feature exists. They do not communicate what makes this product's version of it worth using.

**The forced casual register.** "Hey there 👋" / "Let's get started!" / "You're all set 🎉" applied to B2B interfaces used by people in professional contexts. Casual register reads as approachable on consumer products. On tools used by procurement managers, legal teams, or operations leads, it reads as not understanding who the user is.

**The three-word tagline.** "[Verb] [noun] [adverb/adjective]." "Work smarter, faster." "Build without limits." "Ship with confidence." These are meaningless at the category level. Every product in a category can make this claim.

**The "Made with ❤️ in [city]" footer.** This belongs to a moment in indie web culture. On a product that wants to be taken seriously by buyers, it reads as a signal that the product is a side project.

---

## Image and Asset Defaults

**The stock photo tell.** Diverse teams of people smiling at laptops or in meetings. These images communicate "professional" and "inclusive" by category convention. They do not communicate anything specific about the product.

**The abstract 3D decoration.** Floating orbs, gradient blobs, geometric meshes, or glass-morphic shapes used as hero decoration or background texture. These are generated by AI image tools and 3D libraries as the default "tech product" visual language. They are not assets — they are the absence of a visual direction.

**The Lottie placeholder.** Animated illustrations of generic concepts (data flowing, teams collaborating, checkmarks completing) used as the primary visual content in sections that should carry product-specific proof. These animations communicate category, not product.

**The greyscale logo parade.** A horizontal row of desaturated company logos below the hero as social proof. This component signals scale and credibility by convention. When the logos are recognizable, it works. When they are not — or when the product cannot actually claim those logos as customers — it signals that someone used a template.
