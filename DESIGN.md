---
name: Instituto AG — Dra. Andressa Gomes
description: Warm editorial physiotherapy landing page — paper-toned, hairline-grid, antique gold accents.
colors:
  sand-bg: "#EFECE5"
  sand-bg-alt: "#d6d0c2"
  ink: "#292524"
  stone: "#78716c"
  dust: "#a8a29e"
  hairline: "#a8a29e"
  antique-gold: "#c5a55a"
  antique-gold-light: "#d4bb7a"
  antique-gold-dark: "#a88d3e"
  dark-roast: "#2A2621"
typography:
  display:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "clamp(52px, 10vw, 120px)"
    fontWeight: 200
    lineHeight: 0.9
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "clamp(40px, 6vw, 64px)"
    fontWeight: 200
    lineHeight: 1.1
    letterSpacing: "-0.04em"
  title:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "28px"
    fontWeight: 300
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  body:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 300
    lineHeight: 1.7
    letterSpacing: "normal"
  label:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "11px"
    fontWeight: 300
    lineHeight: 1.2
    letterSpacing: "0.15em"
    textTransform: "uppercase"
rounded:
  pill: "999px"
  xs: "4px"
  sm: "16px"
  md: "20px"
  lg: "32px"
spacing:
  xs: "8px"
  sm: "16px"
  md: "24px"
  lg: "32px"
  xl: "48px"
  xxl: "64px"
  section: "96px"
  section-lg: "128px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.sand-bg}"
    rounded: "{rounded.pill}"
    padding: "16px 32px"
    typography: "{typography.label}"
  button-primary-hover:
    backgroundColor: "{colors.antique-gold-dark}"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.xs}"
    border: "1px solid {colors.hairline}"
    padding: "16px"
    typography: "{typography.label}"
  button-solid-light:
    backgroundColor: "{colors.sand-bg}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xs}"
    padding: "16px"
    typography: "{typography.label}"
  card:
    backgroundColor: "{colors.sand-bg}"
    rounded: "{rounded.md}"
    border: "1px solid {colors.hairline}"
    padding: "{spacing.xl}"
  card-featured:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.sand-bg}"
    rounded: "{rounded.md}"
    padding: "{spacing.xl}"
---

# Design System: Instituto AG — Dra. Andressa Gomes

## Overview

**Creative North Star: "The Warm Editorial Clinic"**

Instituto AG reads like a calm, well-set health journal printed on warm paper — a physiotherapy practice expressed through an editorial grid of hairline rules, generous whitespace, and a restrained antique-gold accent. The aesthetic is humanized and approachable without losing professional precision: type runs light and airy, surfaces stay flat and paper-warm, and the only color that sings is the muted gold used sparingly for icons, highlights, and emphasis.

Depth is felt through tonal layering and structure rather than shadow. Column borders, section rules, and the single deep "dark roast" band do the work of separating content. The result is a measured, confident page that lets the clinician's credibility and patient stories hold the attention — nothing competes with the content.

**Key Characteristics:**
- Flat-by-default, tonal layering; shadows are rare and small.
- Hairline border grid defines every section and column.
- Very light Inter weights (200–300) at large display sizes.
- Antique gold used sparingly — accents, icons, and emphasis only.
- Pill-shaped images and buttons soften the editorial grid with warmth.
- One deep dark-roast section provides the only high-contrast band.

## Colors

A warm, paper-led palette grounded in sand neutrals with a single muted antique-gold accent. Warmth comes from the slightly cream sand base rather than saturated hues.

### Primary

- **Antique Gold** (#c5a55a): The single accent. Used for inline emphasis in headlines (e.g. "equilíbrio"), section icons, list checkmarks, step numbers, and small highlights. Its warmth mirrors the brand's humanized care. Lighter sibling Antique Gold Light (#d4bb7a) appears in gradient accents; deeper Antique Gold Dark (#a88d3e) is the hover state for the primary button.

### Neutral

- **Warm Sand** (#EFECE5): The site background and default surface. A slightly cream off-white that anchors the paper editorial feel. Doubles as the light "white-soft" used on dark surfaces.
- **Tonal Sand** (#d6d0c2): The tonal layer at 20% opacity (`rgba(214,208,194,0.2)`). Used as alternating section backgrounds (philosophy, testimonials, FAQ) and card hover fills.
- **Ink** (#292524): Primary text and the darkest surface. Used for body/headline text, the primary button, and the featured price card.
- **Stone** (#78716c): Secondary text — supporting paragraphs, labels, tags, list items.
- **Dust** (#a8a29e): Muted text — eyebrows, hints, placeholders, meta. Also the basis of the hairline border color at 35% opacity (`rgba(168,162,158,0.35)`).
- **Dark Roast** (#2A2621): The deep warm-near-black used for the Workshops/Event band (`--dark-section`).

### Named Rules

**The Sparing Gold Rule.** Antique gold appears on a small share of any screen — icons, one inline highlight, small numerals. Its rarity is what makes it feel like an accent, not a theme. Never flood a section with it.

**The Warm Paper Rule.** All neutrals lean warm. No cool grays or blue-tinged whites. If a neutral looks cold on the page, it is wrong for this system.

## Typography

**Display Font:** Inter (fallback system-ui, sans-serif)
**Body Font:** Inter (fallback system-ui, sans-serif)

**Character:** One restrained sans-serif family carries the entire system, differentiated by extremely light weights and careful tracking rather than by font changes. The pairing is airy and editorial at large sizes, quietly legible in body text, and disciplined in uppercase tracked labels. Inter's neutrality keeps the warm palette and gold accent from feeling decorative.

### Hierarchy

- **Display** (200, clamp(52px→120px), 0.9): The hero title and oversized statements. Uppercase, tight negative tracking (-0.04em). The single most dramatic moment on the page.
- **Headline** (200, clamp(40px→64px), 1.1): Section titles (philosophy, testimonials, plans, FAQ, workshops). Uppercase, negative tracking, generous breathing room.
- **Title** (300, 28px, 1.2): Service and card titles, feature headings, event names. Uppercase where used as nav labels, sentence-case where used as card titles.
- **Body** (300, 17px, 1.7): Supporting paragraphs and list content. Max width around 420–680px to preserve readability.
- **Label** (300, 11px, 0.15em, uppercase): Eyebrows, tags, stat labels, step numbers, footer titles, meta. The site's structural signposting voice.

### Named Rules

**The Light-First Rule.** Large display and headline text is set at 200–300 weight. Do not bump body or headlines to heavier weights (400–500) for emphasis; the system relies on size, tracking, and case changes instead.

## Layout

The site is contained in a centered `site-wrapper` capped at **1400px** with a 1px hairline left/right border, set against a fixed full-viewport background grid of vertical hairline rules (`bg-lines`). This grid-column structure is the signature: content sits on an invisible editorial column system defined by those fixed lines.

Sections stack vertically, each separated by a **1px hairline border**. Content is broken into full-bleed bands (marquee, services, testimonials, pilates, plans, FAQ, dark workshops) rather than floating cards. Within bands, grids collapse responsively:

- **Hero:** single column on mobile → two columns (left text 2fr, right portrait 1fr) at ≥1024px.
- **Services:** 1 column → 2 columns at ≥768px, separated by a shared hairline.
- **Testimonials:** 1 → 2 → 3 columns at ≥1024px.
- **Plans:** 1 → 3 columns at ≥768px.
- **Pilates cards:** 1 → 2 columns at ≥768px.

**Spacing rhythm:** Section padding scales from **96px** (mobile/desktop) to **128px** (≥1024px) for major sections; content cards use a **32–48px** internal gutter. Vertical rhythm is built on 8px increments (8/16/24/32/48/64).

## Elevation & Depth

The system is **flat by default**, conveying depth through tonal layering and hairline structure rather than shadows. Alternating Warm Sand and Tonal Sand bands create the primary separation; the 1px hairlines delineate columns and sections.

Shadows are rare and small, used only to gently lift a foreground object:

- **Ambient low** (`0 8px 24px -4px rgba(41,37,36,0.2)`): the primary hero button.
- **Soft portrait** (`0 20px 40px -8px rgba(41,37,36,0.15)`): the hero pill portrait.
- **Deep band** (`0 25px 50px -12px rgba(0,0,0,0.3)`): the dark-roast workshops container, to separate it from the paper field.
- **Float glow** (`0 8px 24px rgba(37,211,102,0.35)`): the fixed WhatsApp button.

### Named Rules

**The Flat-by-Default Rule.** Surfaces are flat and paper-toned at rest. Elevation appears only as a hover or foreground response — a gentle shadow on an interactive element, never ambient depth on resting surfaces.

## Shapes

The form language pairs a strict rectangular editorial grid with a single softening device: the **pill (999px radius)**. Pill shapes are reserved for images (the hero portrait, featured event), buttons, and stat chips. Everything else — cards, containers, image tiles — uses gentle rounded corners at **4px, 16px, 20px, or 32px**.

- **Pill** (999px): hero portrait, primary buttons, featured event row (on desktop), event items, WhatsApp float.
- **Large** (32px): dark-roast container and CTA band.
- **Medium** (20px): price cards.
- **Small** (16px): featured event card, event items on mobile.
- **Sharp-ish** (4px): secondary/outline buttons, service image tiles, pilates steps.

Borders are uniformly **1px hairlines** at the Dust 35% opacity color; they trace the editorial structure without weight.

## Components

The component language is **minimal and precise**: restrained shapes, hairline borders, flat paper surfaces, and uppercase tracked labels. Interaction is quiet — a gentle background wash, a light scale, or a color shift — never loud.

### Buttons
- **Shape:** Primary is a pill (999px); secondary/outline and solid-light are sharp (4px). All uppercase with 0.15em tracking, 300 weight.
- **Primary:** Ink background, Warm Sand text, 16px×32px padding, pill radius, `0 8px 24px` ambient shadow. Hover: background shifts to Antique Gold Dark and scales to 1.05; the arrow icon nudges up-right.
- **Outline:** Transparent, 1px hairline border, Ink text, 4px radius. Hover: fills Ink, text flips to Warm Sand.
- **Solid (light):** Warm Sand background, Ink text, 4px radius — used for CTA buttons sitting on dark bands (pilates CTA, featured price card). Hover: washes to a warm tone or gold.

### Cards / Containers
- **Corner Style:** 20px (price cards), 16px (featured event), 32px (CTA/dark band).
- **Background:** Warm Sand default; Tonal Sand wash on hover (`rgba(214,208,194,0.2)`); Ink for the featured price card.
- **Shadow Strategy:** flat at rest (see Elevation). Price cards get no shadow; only the hero portrait and dark band carry one.
- **Border:** 1px hairline for bordered cards; grid cards rely on shared hairline borders between cells.
- **Internal Padding:** 32–48px.

### Price Cards (featured treatment tier)
- **Corner Style:** 20px.
- **Background:** Ink with a soft Antique Gold glow (128px, blur 48px) in the corner; text and price flip to Warm Sand.
- **Border:** 1px hairline; featured card is borderless inside the Ink fill.

### Inputs / Fields (footer newsletter)
- **Style:** Transparent background, no top/side borders — only a 1px hairline bottom stroke.
- **Focus:** Bottom border darkens from Dust to Ink.
- **Placeholder:** Dust. Right-aligned submit arrow button shares the same underline group.

### Navigation
- **Style:** Full-width top bar with a 1px hairline bottom border, 24px×32px padding.
- **Brand:** Round logo (126px) beside stacked uppercase wordmark ("Instituto AG" 300 weight / "Dra. Andressa Gomes" muted tracked label).
- **Links:** Uppercase, 0.15em tracking, 300 weight, Stone color; hover/active shift to Ink.
- **CTA:** Gold "Agendar" link with up-right arrow.
- **Mobile:** Hamburger toggles a stacked full-width menu of uppercase tracked links separated by hairlines; hidden ≥768px.

### Testimonial Cards
- **Corner Style:** none (square within grid), share hairline borders between cells.
- **Background:** Warm Sand; on hover fills Ink, inverting quote text and reviewer name to Warm Sand tones and removing the portrait's grayscale.
- **Content:** Chat icon, quote at 300 weight (17px), reviewer portrait (63px, grayscale at rest) + name + tracked uppercase role.
- **Signature detail:** Avatars and reviewer photos are grayscaled at rest and desaturated on hover — a calm, editorial treatment of people.

### Signature — Hero Pill Portrait
- The hero right column holds a portrait in a vertical **pill (999px)** frame, `aspect-ratio 1/1.6`, max-width 280px, with a 1px gold-tinted hairline and a soft shadow. A gentle GSAP float (`y: -8`, 3s, sine) gives it a subtle breath. This pill silhouette is the page's most distinctive shape.

### Signature — Marquee (Áreas de Atuação)
- A continuous auto-scrolling horizontal band (105s linear marquee) listing areas of expertise as uppercase tracked labels paired with thin-line iconography at 56px. Icons render in Dust and brighten to Ink on hover; the whole track sits at 60% opacity.

### Signature — Dark Workshops Band
- The single dark-roast section (`#2A2621`, 32px radius, 32–96px padding) lists workshops/events. A warm gold blur glow sits behind the heading. The featured event is a pill-shaped card in Warm Sand with a 9:16 portrait; regular events are pill-outlined rows whose titles and arrows brighten to white on hover.

## Do's and Don'ts

### Do:
- **Do** keep surfaces flat, paper-toned (Warm Sand / Tonal Sand), with 1px hairline borders defining structure.
- **Do** reserve Antique Gold for accents — icons, one inline headline highlight, small numerals — and keep it sparse.
- **Do** set display and headline text at Inter 200–300 with tight negative tracking and uppercase; lean on size, not weight, for hierarchy.
- **Do** use uppercase, 0.15em-tracked labels for eyebrows, tags, nav, and stat labels.
- **Do** soften key imagery with the pill (999px) silhouette — portrait, featured event, buttons.
- **Do** keep all neutrals warm; never introduce cool grays or blue-tinted whites.
- **Do** use hairline borders between grid cells rather than floating cards for section content.

### Don't:
- **Don't** flood a section with Antique Gold; its rarity is the point.
- **Don't** add heavy shadows or ambient depth to resting surfaces — depth is tonal and structural.
- **Don't** use heavy (400–600) weights for headlines or body; the system is light-first.
- **Don't** set labels in sentence case or loose tracking; the tracked uppercase voice is structural.
- **Don't** introduce a second display or body font family; Inter alone carries the hierarchy.
- **Don't** cool the palette — a blue or gray paper would break the warm editorial foundation.
