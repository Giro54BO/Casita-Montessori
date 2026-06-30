---
name: Casita Montessori Santa Cruz
description: Warm-clay Montessori sanctuary — humanist serif display, one grounding terracotta, natural surfaces at rest.

colors:
  terracotta: "oklch(62% 0.12 42)"
  terracotta-deep: "oklch(52% 0.12 42)"
  warm-linen: "oklch(97% 0.008 75)"
  natural-white: "oklch(99% 0 0)"
  deep-bark: "oklch(18% 0.015 60)"
  warm-earth: "oklch(30% 0.015 60)"
  mid-clay: "oklch(55% 0.01 60)"
  linen-mist: "oklch(92% 0.005 75)"
  sage: "oklch(70% 0.07 155)"
  terracotta-whisper: "oklch(62% 0.12 42 / 0.12)"
  terracotta-veil: "oklch(62% 0.12 42 / 0.22)"

typography:
  display:
    fontFamily: "Lora, Georgia, serif"
    fontSize: "clamp(2.25rem, 6vw, 3.75rem)"
    fontWeight: 400
    fontStyle: italic
    lineHeight: 1.1
  headline:
    fontFamily: "Lora, Georgia, serif"
    fontSize: "clamp(1.5rem, 3.5vw, 2.25rem)"
    fontWeight: 600
    lineHeight: 1.2
  title:
    fontFamily: "Lora, Georgia, serif"
    fontSize: "clamp(1.125rem, 2.5vw, 1.5rem)"
    fontWeight: 400
    fontStyle: italic
    lineHeight: 1.35
  body:
    fontFamily: "DM Sans, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.65
  body-lead:
    fontFamily: "DM Sans, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.7
  supporting:
    fontFamily: "DM Sans, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "DM Sans, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 600
    letterSpacing: "0.04em"
    textTransform: "uppercase"
  micro-label:
    fontFamily: "DM Sans, system-ui, sans-serif"
    fontSize: "0.6875rem"
    fontWeight: 600
    letterSpacing: "0.1em"
    textTransform: "uppercase"

rounded:
  none: "0"
  sm: "6px"
  md: "12px"
  lg: "20px"
  xl: "32px"
  pill: "9999px"

spacing:
  xs: "8px"
  sm: "16px"
  md: "24px"
  lg: "40px"
  xl: "64px"
  "2xl": "96px"
  "3xl": "140px"

components:
  button-primary:
    backgroundColor: "{colors.terracotta}"
    textColor: "{colors.natural-white}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "14px 32px"
  button-primary-hover:
    backgroundColor: "{colors.terracotta-deep}"
    textColor: "{colors.natural-white}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.terracotta}"
    border: "2px solid {colors.terracotta}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "12px 28px"
  button-whatsapp:
    backgroundColor: "#25D366"
    textColor: "{colors.natural-white}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "14px 32px"
  input-text:
    backgroundColor: "transparent"
    textColor: "{colors.deep-bark}"
    rounded: "{rounded.sm}"
    padding: "10px 14px"
    border: "1px solid {colors.linen-mist}"
  card:
    backgroundColor: "{colors.natural-white}"
    textColor: "{colors.deep-bark}"
    rounded: "{rounded.md}"
    padding: "28px"
  card-feature:
    backgroundColor: "{colors.warm-linen}"
    textColor: "{colors.deep-bark}"
    rounded: "{rounded.lg}"
    padding: "40px"
  nav-link:
    textColor: "{colors.deep-bark}"
    typography: "{typography.body}"
  nav-link-hover:
    textColor: "{colors.terracotta}"
---

# Design System: Casita Montessori Santa Cruz

## 1. Overview: The Warm Montessori Home

**Creative North Star: "The Warm Montessori Home"**

The Casita Montessori site reads like a thoughtful, well-organized home — not an institution, not a startup, not a generic daycare brochure. Natural materials, breathing room, and a single grounding terracotta accent that signals warmth and trustworthiness without veering into the infantile. The interface feels **unhurried, honest, and close** — the visual equivalent of a calm educator who has seen hundreds of first-day nerves and knows exactly how to make a parent feel safe.

The aesthetic philosophy is **warmth through natural restraint**. Every visual decision should evoke a well-prepared Montessori environment: clean surfaces, natural materials, nothing excessive. The palette is dominated by linen and clay tones — the colors of wood, woven baskets, and natural cotton — with a single terracotta accent that is warm without being aggressive.

This system explicitly rejects: bright rainbow palettes, cartoon animals or commercial characters, dark moody aesthetics, generic SaaS blue-and-white templates, premium marble finishes, and the visual language of corporate schools. When in doubt, do less, warmer, and more specific.

**Key Characteristics:**
- Warm linen off-white as the page ground — imperceptibly tinted toward clay for subliminal warmth.
- One terracotta accent used on CTAs, active states, and sparse emphasis moments. Rarity is the point.
- Italic serif for display; clean humanist sans for body at 1.65 line-height.
- Pill-shaped CTAs — round and approachable, not the sharp-edged editorial of a design publication.
- Natural surfaces at rest. Shadows only on hover or deliberate card elevation.
- Generous, magazine-scale spacing between sections; tighter rhythms within content groups.

## 2. Colors: The Clay-and-Linen Palette

A two-chord palette: warm linen neutrals grounded in clay undertones, plus one decisive terracotta accent. The terracotta sits in the same hue family as natural clay, wood, and dried leaves — inherently Montessori. No secondary accent is added; restraint is doctrinal.

### Primary
- **Terracotta** (oklch(62% 0.12 42)): The one warm voice. Primary CTAs, active navigation states, icon accents, section emphasis. Never as a background wash. Never as a gradient. Rarity makes it trustworthy rather than loud.

### Neutral
- **Warm Linen** (oklch(97% 0.008 75)): Primary page background. Near-white with an imperceptible clay tint that creates cohesion with Terracotta and reads as natural, not cold. Used on `body` and standard surfaces.
- **Natural White** (oklch(99% 0 0)): Elevated surfaces. Cards lifted against Warm Linen. Never the page background alone — too clean and corporate without the linen warmth.
- **Deep Bark** (oklch(18% 0.015 60)): Primary text. Warm-tinted near-black — reads as grounded and confident on linen without the harshness of pure black.
- **Warm Earth** (oklch(30% 0.015 60)): Secondary text — lead paragraphs, subheadings, supporting copy. Clearly subordinate to Deep Bark; still warm.
- **Mid Clay** (oklch(55% 0.01 60)): Tertiary text — micro-labels, captions, schedule details, address lines. Intentionally recessed; reads as metadata.
- **Linen Mist** (oklch(92% 0.005 75)): Hairline borders, dividers, section separators. The structural seams of the layout, barely visible.
- **Sage** (oklch(70% 0.07 155)): Reserved for a single secondary accent use — the "Agendar una visita" secondary CTA border, or an occasional nature-adjacent decorative touch. Not part of the core text or CTA system.

### Accent Alpha Variants
- **Terracotta Deep** (oklch(52% 0.12 42)): Hover/pressed state for Terracotta. A confident small darkening.
- **Terracotta Whisper** (oklch(62% 0.12 42 / 0.12)): Diffuse glow behind hover states on cards; subtle selection tint.
- **Terracotta Veil** (oklch(62% 0.12 42 / 0.22)): Focus rings, emphasis shells, active FAQ panel backgrounds.

### Named Rules

**The One Warmth Rule.** Terracotta is the only chromatic color in the system. Sage exists as a single-use secondary accent for the secondary CTA only. No other hues are introduced. If a layout wants a second emphasis point, use scale, weight, or spacing — never a second hue.

**The Linen-Not-White Rule.** Page background is Warm Linen, never Natural White. Pure white is reserved for elevated card surfaces. Warmth is load-bearing: without it, the site reads as clinical and the terracotta reads as aggressive rather than welcoming.

**The OKLCH-Only Rule.** All new colors must be declared in OKLCH. The single exception is the WhatsApp button (#25D366), which is a brand color that must not be altered.

## 3. Typography: The Italic Serif and the Friendly Sans

**Display Font:** Lora (with Georgia fallback) — a contemporary text-optimized serif with warm curves and strong italic character. Trustworthy without being stuffy.
**Body Font:** DM Sans (with system-ui fallback) — a geometric humanist sans with subtle warmth; highly readable at small sizes; feels friendly without being childish.

**Character:** Display type uses Lora in its italic cut for headlines — editorial but approachable, evoking handwriting and warmth rather than institutional formality. Body copy uses DM Sans for maximum legibility across devices and user demographics (some parents may be on low-resolution screens). There is no monospace level in this system; the product has no technical register.

### Hierarchy

- **Display** (Lora, weight 400, italic, clamp(2.25rem, 6vw, 3.75rem), line-height 1.1): Hero title only. Italic serif reads as a warm, human voice — closer to a name on a door than a headline in an ad.
- **Headline** (Lora, weight 600, clamp(1.5rem, 3.5vw, 2.25rem), line-height 1.2): Section headings. Upright, authoritative, still warm.
- **Title** (Lora, weight 400, italic, clamp(1.125rem, 2.5vw, 1.5rem), line-height 1.35): Section taglines, pull quotes, the single phrase that sits below a headline. A quieter secondary display voice.
- **Body** (DM Sans, weight 400, 1rem, line-height 1.65): Paragraph copy. Max 60–70ch for readability.
- **Body Lead** (DM Sans, weight 400, 1.0625rem, line-height 1.7): The opening paragraph of each section. Slightly larger and more relaxed.
- **Supporting** (DM Sans, weight 400, 0.875rem, line-height 1.65): Captions, footnotes, schedule details, address lines.
- **Label** (DM Sans, weight 600, 0.875rem, uppercase, letter-spacing 0.04em): CTA button labels. Short, imperative, clear.
- **Micro-Label** (DM Sans, weight 600, 0.6875rem, uppercase, letter-spacing 0.1em): Section category tags — "Zona Norte", "Taller 1", "Horarios", small navigational metadata.

### Named Rules

**The Italic-Is-Welcome Rule.** Italic is a tone choice for display type, signaling warmth and human presence. It is not used for body emphasis. Body emphasis is carried by weight (DM Sans 600) or by line isolation. Italicizing body copy dilutes the display voice and reads as academic rather than warm.

**The 1.65 Leading Rule.** Body line-height is 1.65. This is the minimum comfortable reading density for parents scanning on mobile. Not 1.5 (too tight for DM Sans), not 1.8 (loses reading rhythm). This is fixed.

**The Fluid-Headlines-Only Rule.** Headings use `clamp()` fluid sizing. Body and labels use fixed `rem`. Fluid body sizes cause uncomfortable reflow on mid-range widths.

## 4. Elevation

Flat by default. The product is a trust-building page, not an app — surfaces rest on a single warm layer. Depth appears only in response to interaction (hover, active) or deliberate structural elevation (a featured card rising from the linen background).

### Shadow Vocabulary

- **Soft Hover Lift** (`0 4px 20px -4px rgba(100, 60, 30, 0.10), 0 1px 3px rgba(0,0,0,0.05)`): Default hover response on cards. Warm-tinted diffuse shadow; barely perceptible at rest, clear on interaction.
- **Card Elevation** (`0 12px 32px rgba(100, 60, 30, 0.08)`): Deliberate surface lift — a featured section card, a schedule block, the FAQ panel. Low alpha.
- **Terracotta Glow** (`0 16px 48px var(--color-terracotta-whisper)`): The one moment of magnetic warmth. Reserved for the primary CTA block or a single featured trust element. Used once per page maximum.
- **Tooltip / Floating** (`0 2px 10px rgba(0,0,0,0.10)`): Tight shadow for small floating elements.

### Named Rules

**The Warm-Shadow Rule.** Shadows carry a faint warm-brown tint (rgba(100, 60, 30, …)) rather than pure black. On a linen background, warm shadows read as natural; black shadows read as cold and graphic.

**The Flat-By-Default Rule.** Cards are flat at rest. A Linen Mist hairline border articulates a surface before a shadow is considered. Shadow is earned by interaction or explicit elevation.

**The Low-Alpha Rule.** No shadow exceeds 0.12 alpha on its strongest layer. Higher alphas read as dramatic rather than calm.

## 5. Components

### Buttons

- **Shape:** Pill-shaped (`border-radius: 9999px`). Round and approachable — the opposite of the sharp editorial CTA. Matches the product's warmth register. This is a conscious departure from Montessori's "squared" material aesthetic; parents respond to pill CTAs as friendlier and more inviting on mobile.
- **Primary (WhatsApp CTA):** WhatsApp green (#25D366) background, Natural White text. This is the conversion nucleus of the page. Padding 14px / 32px. Weight 600, uppercase, letter-spacing 0.04em.
- **Primary (General):** Terracotta background, Natural White text. Same sizing as WhatsApp CTA. Used for non-WhatsApp primary actions.
- **Hover:** `transform: translateY(-2px)` + background shifts to Terracotta Deep. Transition 200ms ease-out. Confident lift, no bounce.
- **Focus:** Visible Terracotta Veil ring (2px outline, 2px offset). Keyboard-accessible.
- **Secondary:** Pill-shaped, transparent background, Terracotta border (2px), Terracotta text. Used for "Agendar una visita". Hover fills to Terracotta.
- **No ghost/text-only buttons** for primary actions. Every CTA on this page must be legible to a parent scanning on mobile while multitasking.

### Cards & Containers

- **Corner style:** Controlled vocabulary — 6px (tight inline callouts, badges), 12px (standard feature cards, FAQ items), 20px (featured trust section, day-in-the-life timeline card), 32px (hero image frames). Radius scales with visual weight.
- **Background:** Natural White on Warm Linen for standard cards; Warm Linen on Natural White for inverted surface moments.
- **Shadow:** Flat at rest; Soft Hover Lift on interactive cards.
- **Border:** 1px Linen Mist for non-interactive surfaces needing articulation without shadow.
- **Internal padding:** 24–28px for standard cards; 40px for featured section blocks; 16px for tight timeline items.

### Navigation

- **Site Header:** Compact bar, left-aligned logo (horizontal SVG lockup), right-aligned navigation links + WhatsApp CTA button.
- **Typography:** DM Sans, weight 500, 0.9rem. Sentence case, not all-caps — friendly and readable.
- **Default:** Deep Bark text on Warm Linen.
- **Hover / Active:** Smooth color transition to Terracotta, 200ms. No underline at rest; on active page, a 2px Terracotta underline appears.
- **Mobile:** Hamburger icon opens a drawer from the right. Drawer background is Natural White. All nav links at 1.25rem for easy tap targets.
- **Sticky behavior:** Header sticks on scroll, gains a 1px Linen Mist bottom border and a subtle Soft Hover Lift shadow to separate it from page content.

### Trust Indicators (signature component)

A horizontal row of 4–5 compact trust chips near the top of the page (below the hero CTA). Each chip is a Natural White pill with a Linen Mist border, a small terracotta icon (camera, shield, clock, location pin), and a 2–3 word label in Micro-Label style. Examples: "Cámaras en vivo", "Entrega controlada", "Ambientes seguros", "Zona Norte + Urubó". These chips are the fastest-loading trust signals on the page and must appear above the fold on all devices.

### Daily Routine Timeline

The "Un día en Casita Montessori" section uses a vertical timeline on mobile and a horizontal stepped layout on desktop. Each step is a Natural White card (12px radius, Card Elevation shadow) with a Terracotta step number (Headline size, lightly opaque), a Lora italic title, and a DM Sans body description. The connector between steps is a 1px Linen Mist line. No icons required — the numbered sequence is the navigation.

### FAQ Accordion

- Closed state: question in DM Sans 600, Deep Bark, full-width, 1px Linen Mist bottom border, chevron in Mid Clay.
- Open state: Terracotta Veil background fill, Terracotta chevron rotated 180°, answer in DM Sans 400 Body with 1.65 leading. Smooth max-height transition, 250ms ease-out.
- Never nest accordion items inside a card. The accordion IS the container.

### WhatsApp CTA Block (primary conversion section)

Appears at minimum twice: once in the hero, once as the page's final section. Final block: Natural White surface (Card Elevation), centered, headline in Lora 600, lead paragraph in Body Lead, then two buttons: primary WhatsApp CTA, secondary "Agendar una visita". Max width 560px, horizontally centered, 48px vertical padding. This block must never be buried below the fold on any breakpoint.

### Layout & Spacing

- **Max width:** Prose and content blocks cap at 820px; page containers at 1280px. Prose further constrained to 60–70ch.
- **Spacing scale:** 8 / 16 / 24 / 40 / 64 / 96 / 140px. The 4px sub-step is omitted — this is a warm editorial scale, not a dense app-UI scale.
- **Section rhythm:** 96–140px between top-level page sections; 40–64px between content groups within a section; 8–24px inside tight clusters.
- **Grid:** Mobile-first single column. Tablet: asymmetric two-column for hero (text left, image right) and trust chips row. Desktop: `repeat(auto-fit, minmax(260px, 1fr))` for feature and development benefit grids.
- **Motion:** 150ms for color/opacity; 250–350ms for transforms; 500–800ms for orchestrated page entrances. All use `cubic-bezier(0.16, 1, 0.3, 1)` (expo-out). `prefers-reduced-motion` collapses every non-essential transition.

## 6. Do's and Don'ts

### Do:

- **Do** use Warm Linen as the page background. Natural White is for elevated surfaces only — see The Linen-Not-White Rule.
- **Do** use Terracotta on ≤10% of any given screen. Scarcity signals warmth, not noise — see The One Warmth Rule.
- **Do** declare all new colors in OKLCH. The only hex exception is the WhatsApp brand green.
- **Do** use Lora italic for display and title type as a tone of voice, not for body emphasis.
- **Do** use `clamp()` fluid sizing for headings; fixed `rem` for body and labels — see The Fluid-Headlines-Only Rule.
- **Do** keep CTAs pill-shaped. This is the friendliness signature of the system.
- **Do** use warm-brown tinted shadows (rgba(100, 60, 30, …)), not pure-black shadows.
- **Do** keep surfaces flat at rest. Reach for shadows only on hover or deliberate elevation.
- **Do** respect `prefers-reduced-motion` on every animation.
- **Do** ensure the WhatsApp CTA appears above the fold and at the bottom of the page.
- **Do** include alt text on all images of children, describing the activity rather than the child.

### Don't:

- **Don't** use pure black (#000) or pure white (#fff). Always use the warm tinted neutrals.
- **Don't** use rainbow or primary-color palettes. The palette is natural and restrained.
- **Don't** use cartoon characters, Disney imagery, princess/superhero motifs, or commercial characters anywhere in the visual system.
- **Don't** use `border-left` colored stripes on cards or list items. This is a generic dashboard pattern that conflicts with the warm home aesthetic.
- **Don't** use gradient text or gradient backgrounds (other than photography). Flat surfaces only.
- **Don't** add a second chromatic accent beyond Terracotta and the single Sage use for the secondary CTA. If a layout wants more color, use scale or weight.
- **Don't** use bounce or elastic easing. Expo-out is the signature. Real, warm, decelerating.
- **Don't** animate layout properties (`width`, `height`, `padding`, `margin`). Use `transform` and `opacity` only.
- **Don't** nest cards inside cards. The hierarchy is flat: Warm Linen → Natural White card → content.
- **Don't** use identical-size feature grids with icon + heading + text repeated six times. Vary the layout rhythm.
- **Don't** use institutional or corporate photography (posed studio shots, stock photo diversity displays). Images should show children doing specific Montessori activities with real materials.
- **Don't** use dark mode. This site is a warm, light-mode reading experience. Dark mode with terracotta accents would read as moody rather than welcoming.
- **Don't** use glassmorphism, blur effects, or translucent card treatments.
- **Don't** promise what the brief explicitly disallows: bilingual education, Montessori certification, premium infrastructure, or 100% safety guarantees.
- **Don't** use hedging copy. Every sentence on this page must be a statement, not a suggestion.
