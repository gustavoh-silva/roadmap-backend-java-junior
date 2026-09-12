---
version: alpha
name: Nocturne-gallery-design
description: A dark-only competence-gate dashboard that fuses Apple's tile rhythm with Raycast's inky developer chrome. Alternating near-black tiles carry Inter typography with the ss03 stylistic set, hairline 1px borders, 18px cards, and a single Action Sky (#2997ff) accent family — with the primary CTA rendered in a deeper AA-safe blue (#0071e3, 4.7:1). A ⌘K filter search, custom checkboxes, priority pills, and evidence-level segments make a static single-file page feel like a product. The signature moment is a restrained blue-glow hero wash behind a 56px tight-tracked headline, paired with a live "next blocker" card.

colors:
  primary: "#2997ff"
  primary-focus: "#0071e3"
  primary-pressed: "#1f8af0"
  on-primary: "#ffffff"
  ink: "#f4f4f6"
  body: "#cdcdcd"
  mute: "#9c9c9d"
  ash: "#9a9a9b"
  stone: "#8f8f90"
  on-dark: "#ffffff"
  on-dark-mute: "rgba(255,255,255,0.72)"
  canvas: "#07080a"
  tile-1: "#0d0d0f"
  tile-2: "#121215"
  tile-3: "#1a1b1e"
  frosted: "rgba(7,8,10,0.8)"
  hairline: "#242728"
  hairline-soft: "rgba(255,255,255,0.08)"
  hairline-strong: "rgba(255,255,255,0.16)"
  accent-blue: "#57c1ff"
  accent-blue-soft: "rgba(87,193,255,0.15)"
  accent-red: "#ff6161"
  accent-red-soft: "rgba(255,97,97,0.15)"
  accent-green: "#59d499"
  accent-green-soft: "rgba(89,212,153,0.15)"
  accent-yellow: "#ffc533"
  accent-yellow-soft: "rgba(255,197,51,0.15)"
  hero-glow-start: "#2997ff"
  hero-glow-end: "#0a1930"

typography:
  hero-display:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 56px
    fontWeight: 600
    lineHeight: 1.07
    letterSpacing: -0.28px
    fontFeature: '"calt", "kern", "liga", "ss03"'
  tile-headline:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 40px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -0.2px
    fontFeature: '"calt", "kern", "liga", "ss03"'
  eyebrow:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 12.5px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0.06em
    fontFeature: '"calt", "kern", "liga", "ss03"'
  lede:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 21px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: -0.1px
    fontFeature: '"calt", "kern", "liga", "ss03"'
  body:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.47
    letterSpacing: -0.15px
    fontFeature: '"calt", "kern", "liga", "ss03"'
  card-title:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 20px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0.2px
    fontFeature: '"calt", "kern", "liga", "ss03"'
  card-big:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 24px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0.2px
    fontFeature: '"calt", "kern", "liga", "ss03"'
  section-title:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 18px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
    fontFeature: '"calt", "kern", "liga", "ss03"'
  body-sm:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
    fontFeature: '"calt", "kern", "liga", "ss03"'
  caption-md:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
    fontFeature: '"calt", "kern", "liga", "ss03"'
  caption:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.12px
    fontFeature: '"calt", "kern", "liga", "ss03"'
  micro-label:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 11px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0.04em
    fontFeature: '"calt", "kern", "liga", "ss03"'
  button:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 15px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0.1px
    fontFeature: '"calt", "kern", "liga", "ss03"'
  button-small:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
    fontFeature: '"calt", "kern", "liga", "ss03"'
  nav-mini:
    fontFamily: "Inter, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.12px
    fontFeature: '"calt", "kern", "liga", "ss03"'

rounded:
  none: 0px
  xs: 4px
  sm: 5px
  md: 8px
  lg: 18px
  pill: 9999px

spacing:
  xxs: 2px
  xs: 4px
  sm: 8px
  md: 10px
  lg: 12px
  xl: 16px
  xxl: 24px
  xxxl: 32px
  section: 80px

components:
  global-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.on-dark}"
    typography: "{typography.nav-mini}"
    height: 44px
  sub-nav-frosted:
    backgroundColor: "{colors.frosted}"
    textColor: "{colors.ink}"
    typography: "{typography.button-small}"
    height: 52px
  button-primary:
    backgroundColor: "{colors.primary-focus}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 11px 22px
  button-primary-active:
    backgroundColor: "{colors.primary-pressed}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.pill}"
  button-primary-focus:
    backgroundColor: "{colors.primary-focus}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.pill}"
  button-small:
    backgroundColor: "{colors.primary-focus}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-small}"
    rounded: "{rounded.pill}"
    padding: 8px 16px
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 11px 22px
  hero-tile:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.hero-display}"
    rounded: "{rounded.none}"
    padding: 72px 24px 56px
  hero-glow:
    backgroundColor: "{colors.hero-glow-start} → {colors.hero-glow-end}"
    rounded: "{rounded.none}"
    opacity: 0.28
  palette-card:
    backgroundColor: "{colors.tile-1}"
    textColor: "{colors.on-dark}"
    typography: "{typography.card-title}"
    rounded: "{rounded.lg}"
    padding: 24px
  palette-card-shadow:
    backgroundColor: "{colors.tile-1}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.lg}"
    padding: 24px
  progress-bar-row:
    backgroundColor: "{colors.tile-1}"
    textColor: "{colors.mute}"
    typography: "{typography.caption-md}"
    rounded: "{rounded.lg}"
    padding: 16px 20px
  steps-stepper:
    backgroundColor: "{colors.tile-1}"
    textColor: "{colors.body}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: 8px 24px
  palette-search:
    backgroundColor: "{colors.tile-2}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: 12px 20px
    height: 44px
  keycap:
    backgroundColor: "{colors.tile-2}"
    textColor: "{colors.body}"
    typography: "{typography.caption-md}"
    rounded: "{rounded.xs}"
    padding: 1px 6px
    height: 20px
  gate-trail-badge:
    backgroundColor: "{colors.tile-3}"
    textColor: "{colors.on-dark-mute}"
    typography: "{typography.caption}"
    rounded: "{rounded.xs}"
    padding: 2px 6px
  gate-card:
    backgroundColor: "{colors.tile-2}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: 24px
  criterion-row:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 8px
  criterion-checkbox:
    backgroundColor: "{colors.tile-3}"
    rounded: "{rounded.sm}"
    size: 17px
  prio-pill-core:
    backgroundColor: "{colors.accent-red-soft}"
    textColor: "{colors.accent-red}"
    typography: "{typography.micro-label}"
    rounded: "{rounded.pill}"
    padding: 2px 10px
  prio-pill-comp:
    backgroundColor: "{colors.accent-yellow-soft}"
    textColor: "{colors.accent-yellow}"
    typography: "{typography.micro-label}"
    rounded: "{rounded.pill}"
    padding: 2px 10px
  prio-pill-avanc:
    backgroundColor: "{colors.accent-blue-soft}"
    textColor: "{colors.accent-blue}"
    typography: "{typography.micro-label}"
    rounded: "{rounded.pill}"
    padding: 2px 10px
  prio-pill-front:
    backgroundColor: "{colors.accent-green-soft}"
    textColor: "{colors.accent-green}"
    typography: "{typography.micro-label}"
    rounded: "{rounded.pill}"
    padding: 2px 10px
  practice-tag:
    backgroundColor: "transparent"
    textColor: "{colors.accent-yellow}"
    typography: "{typography.micro-label}"
    rounded: "{rounded.pill}"
    padding: 1px 8px
  project-box:
    backgroundColor: "{colors.tile-1}"
    textColor: "{colors.body}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 14px 16px
  pill-tab:
    backgroundColor: "transparent"
    textColor: "{colors.body}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  pill-tab-active:
    backgroundColor: "{colors.tile-3}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  evidence-link-input:
    backgroundColor: "{colors.tile-2}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.pill}"
    padding: 10px 18px
  section-card:
    backgroundColor: "{colors.tile-2}"
    textColor: "{colors.body}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: 24px
  dont-chip:
    backgroundColor: "{colors.tile-1}"
    textColor: "{colors.mute}"
    typography: "{typography.caption-md}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  vaga-input:
    backgroundColor: "{colors.tile-1}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 10px 14px
  vaga-item:
    backgroundColor: "{colors.tile-1}"
    textColor: "{colors.body}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 12px 14px
  dif-card:
    backgroundColor: "{colors.tile-2}"
    textColor: "{colors.body}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: 20px 22px
  footer-band:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.mute}"
    typography: "{typography.caption}"
    padding: 64px 24px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.body}"
---

## Overview

The Roadmap Java Backend → Júnior dashboard is a **dark-only, single-file competence tracker**: one `index.html`, no build step, no framework, GitHub Pages hosting, progress in `localStorage`. Its design language — **Nocturne Gallery** — fuses Apple's tile rhythm (alternating full-bleed sections, slim dual nav, pill CTAs, tight-tracked Inter headlines) with Raycast's inky developer chrome (near-black canvas `#07080a`, surface ladder, hairline 1px borders, `⌘K` filter search, keycaps, pill tabs, `ss03` Inter).

The page's thesis is stated up front and enforced by the system: **"Você não precisa saber tudo. Precisa conseguir fazer."** Checkbox alone is never proof — every gate pairs criteria with a mandatory project validated by evidence level + link. The hero converts this into action with a live **"Próximo bloqueio"** card: the first pending CORE criterion, always one click from its gate.

**Key Characteristics:**
- Single dark surface mode with a 4-step ladder: `{colors.canvas}` (#07080a) → `{colors.tile-1}` (#0d0d0f) → `{colors.tile-2}` (#121215) → `{colors.tile-3}` (#1a1b1e)
- One accent family, Action Sky `{colors.primary}` (#2997ff), with the primary CTA rendered one notch deeper in `{colors.primary-focus}` (#0071e3) so white text passes AA (4.7:1)
- Inter with `font-feature-settings: "calt", "kern", "liga", "ss03"` enabled site-wide on `body`
- Hairline 1px borders (`{colors.hairline}` #242728, plus soft/strong white-alpha variants) carry every card edge; the single drop-shadow in the system sits under the hero objective card
- Priority pills map 1:1 onto the four accents — CORE red, COMP yellow, AVANC blue, FRONT green — each as saturated text on its own 15%-alpha soft wash
- Evidence ladder ESTUDADO → PRATICADO → APLICADO → COMPROVADO as `{component.pill-tab}` segments; only COMPROVADO + link counts toward a gate
- Gate cards cycle tile surfaces (`tile-1/2/3`) so the section color change itself acts as the divider

## Colors

> **Source:** the `:root` block of `index.html` — the only palette definition in the repo. Tokens below name the exact custom properties.

### Brand & Accent
- **Action Sky** (`{colors.primary}` — #2997ff): the brand voice. Eyebrow labels, ghost-button text/border, inline links, gate-trail "now" badge, hierarchy stepper marker, hierarchy glow start. Never used as a button fill (white-on-#2997ff is 3.02:1 and fails AA).
- **CTA Blue** (`{colors.primary-focus}` — #0071e3): the primary button fill. White text on it is 4.7:1 — the minimum-contrast, maximum-brand compromise. Also the keyboard focus-ring color on ghost/pill/practice controls.
- **Pressed Blue** (`{colors.primary-pressed}` — #1f8af0): active/press fill for the primary button, paired with `transform: scale(0.95)`.
- **On Primary** (`{colors.on-primary}` — #ffffff): button label white. Appears as text only on `{colors.primary-focus}`.

### Surface
- **Canvas** (`{colors.canvas}` — #07080a): page background, hero, footer, global nav. The dominant surface.
- **Tile 1** (`{colors.tile-1}` — #0d0d0f): alternating section background; palette cards; project boxes; vaga inputs; "don't" chips.
- **Tile 2** (`{colors.tile-2}` — #121215): alternating section background; gate cards (on tile-1 sections); search field; evidence-link input; section/dif cards.
- **Tile 3** (`{colors.tile-3}` — #1a1b1e): alternating section background; progress-track fill; checkbox fill; active pill-tab; trail badges; streak pill.
- **Frosted** (`{colors.frosted}` — `rgba(7,8,10,0.8)`): sub-nav background, always paired with `backdrop-filter: saturate(180%) blur(20px)`.
- **Hairline** (`{colors.hairline}` — #242728): the universal 1px card/nav border.
- **Hairline Soft** (`{colors.hairline-soft}` — `rgba(255,255,255,0.08)`): progress-track inner border.
- **Hairline Strong** (`{colors.hairline-strong}` — `rgba(255,255,255,0.16)`): checkbox ring, focused-input border, golden-box border, active pill-tab border.

### Text
- **Ink** (`{colors.ink}` — #f4f4f6): hero headline, section headlines. Off-white for tonal coherence with the canvas.
- **Body** (`{colors.body}` — #cdcdcd): default paragraph text (12.6:1 on canvas).
- **Mute** (`{colors.mute}` — #9c9c9d): secondary copy, metadata, struck-through completed criteria (7.3:1).
- **Ash** (`{colors.ash}` — #9a9a9b): lowest-emphasis small text — placeholders, 11–12px labels, criteria headers (7.1:1; deliberately lifted from the original `#6a6b6c`, which failed at 3.75:1).
- **Stone** (`{colors.stone}` — #8f8f90): footer sources, strikethrough decoration, dif-card fit line (6.2:1; lifted from `#434345`, which failed at 2.03:1).
- **On Dark** (`{colors.on-dark}` — #ffffff): interactive-state primary text — criterion rows, card titles, inputs.
- **On Dark Mute** (`{colors.on-dark-mute}` — `rgba(255,255,255,0.72)`): trail badges and other translucent secondary text on dark surfaces.

### Semantic
- **Accent Blue** (`{colors.accent-blue}` — `#57c1ff`) + **Soft** (`{colors.accent-blue-soft}`): AVANC priority pill; info accents.
- **Accent Red** (`{colors.accent-red}` — `#ff6161`) + **Soft** (`{colors.accent-red-soft}`): CORE priority pill; gate "not ready" status; reset-button danger hover.
- **Accent Green** (`{colors.accent-green}` — `#59d499`) + **Soft** (`{colors.accent-green-soft}`): FRONT pill; gate "done" status; frontend progress bar; optional-trail marker.
- **Accent Yellow** (`{colors.accent-yellow}` — `#ffc533`) + **Soft** (`{colors.accent-yellow-soft}`): COMP pill; gate "almost" status; G2 progress bar; practice tag; storage warning.
- Priority is never carried by position or icon — pill text + wash is the single encoding (CORE red, COMP yellow, AVANC blue, FRONT green).

### Brand Gradient
- **Hero Glow** — one linear wash, `115deg, transparent 20% → {colors.hero-glow-start} 45% → {colors.hero-glow-end} 70% → transparent 90%`, at `opacity: 0.28`, absolutely positioned and pointer-transparent behind the hero copy. The system's only chromatic gradient on chrome; it is fully clipped by the hero (`overflow: hidden`) and must never contribute to page scroll width.

## Typography

### Font Family
**Inter** (Google Fonts, weights 400/500/600) with system fallback `-apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif`. `body` enables `font-feature-settings: "calt", "kern", "liga", "ss03"` — the **ss03** alternate `g` is the same signature detail as the reference system, and every typography token inherits it.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.hero-display}` | 56px | 600 | 1.07 | -0.28px | Hero `h1` (→ 34px ≤640px, → 28px ≤419px) |
| `{typography.tile-headline}` | 40px | 600 | 1.10 | -0.2px | Section `h2` (→ 28px ≤640px) |
| `{typography.eyebrow}` | 12.5px | 400 | 1.5 | 0.06em uppercase | Kicker above hero and hierarchy |
| `{typography.lede}` | 21px | 400 | 1.4 | -0.1px | Hero lede, max 62ch |
| `{typography.body}` | 17px | 400 | 1.47 | -0.15px | Default paragraph; search input |
| `{typography.card-title}` | 20px | 500 | 1.4 | 0.2px | Palette/hero card titles; gate titles |
| `{typography.card-big}` | 24px | 500 | 1.4 | 0.2px | Hero "Java Backend" / next-blocker headline |
| `{typography.section-title}` | 18px | 500 | 1.4 | 0 | Secondary section-card titles |
| `{typography.body-sm}` | 14px | 400 | 1.6 | 0 | Criterion rows, card copy, inputs, footer notes |
| `{typography.caption-md}` | 13px | 400 | 1.4 | 0 | Bar labels, gate meta, "don't" chips |
| `{typography.caption}` | 12px | 400 | 1.5 | -0.12px | Trail badges, dif mini, footer, ref-time |
| `{typography.micro-label}` | 11px | 600 | 1.5 | 0.04em | Priority pills, criteria headers, practice tag |
| `{typography.button}` | 15px | 500 | 1.4 | 0.1px | Primary/ghost buttons |
| `{typography.button-small}` | 14px | 500 | 1.4 | 0 | Small buttons, sub-nav |
| `{typography.nav-mini}` | 12px | 400 | 1.5 | -0.12px | Global nav, streak pill |

### Principles
- **Negative tracking on display, positive micro-tracking on labels.** Headlines tighten (`-0.28 → -0.1px`); 11px labels open slightly (`0.04–0.06em`) to stay legible at small sizes.
- **Body at 17px, not 16px.** Same reading-pace decision as the reference system; search input inherits it.
- **Weight 500 is structural.** Card titles, gate titles, buttons, and mini-labels sit at 500/600 — never 700 anywhere in the system.
- **Uppercase is reserved for metadata.** Eyebrow, criteria headers, ref-time, and fit lines only; never for body copy or buttons.
- **Gate titles never duplicate section headlines.** The card header shows `G2 · Meta 90%`; the full title lives only in the section `h2`.

## Layout

### Spacing System
- **Base unit:** 8px (2px reserved for pill/chip internal tweaks).
- **Tokens:** `{spacing.xxs}` 2px · `{spacing.xs}` 4px · `{spacing.sm}` 8px · `{spacing.md}` 10px · `{spacing.lg}` 12px · `{spacing.xl}` 16px · `{spacing.xxl}` 24px · `{spacing.xxxl}` 32px · `{spacing.section}` 80px.
- **Section vertical padding:** `{spacing.section}` (80px) with 24px gutters; 48px/16px at ≤640px.
- **Card padding:** `{spacing.xxl}` (24px) for palette/gate/section cards; 14–20px for inner rows and boxes.
- **In-row rhythm:** criterion rows pad 8px with 10px gaps; evidence segments gap 8px; trail badges gap 8px.

### Grid & Container
- **Max width:** 1240px (`.wrap`, `.hero-inner`, footer rows) with 24px gutters (16px at ≤640px).
- **Hero grid:** `2fr 3fr` with a 24px gap (never `% + gap`, which overflowed the container by exactly one gutter); stacks to 1 column at ≤1023px. Every grid child carries `min-width: 0`.
- **Measure caps:** lede at 62ch, golden rule box at 70ch, tile-head at 760px, search at 720px.
- **Global guard:** `overflow-x: clip` on `body` plus `min-width: 0` + `overflow-wrap: anywhere` on flexible criterion text — the trio that fixed the 582px mobile overflow.

### Whitespace Philosophy
Whitespace is the pedestal, but the page is a working tool, not a gallery wall: 80px section padding with 32px tile-head margins, 40px between hero copy and the dashboard grid. Inside cards the system runs tight (8–16px rows) because criterion lists are scanned, not read. The footer is the only dense zone — actions row, storage warning, and source line stacked at 12px.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No border, no shadow | Canvas blocks, hero copy, footer body, trail badges |
| Hairline border | 1px solid `{colors.hairline}` (#242728) | Every card, nav bars, inputs at rest |
| Hairline strong | 1px solid `{colors.hairline-strong}` | Checkbox ring, focused inputs, active pill-tab |
| Frosted blur | `saturate(180%) blur(20px)` on `{colors.frosted}` | Sub-nav floating over content |
| Hero shadow | `rgba(0,0,0,0.6) 0 8px 40px` | Objective card in the hero — the only drop-shadow in the system |

**Shadow philosophy.** One shadow, on one card, to lift the dashboard above the hero wash. All other elevation comes from the surface ladder (canvas → tile-1 → tile-2 → tile-3) and the frosted sub-nav. Never add shadows to buttons, pills, or text.

### Decorative Depth
- **Hero glow wash** (`{component.hero-glow}`) supplies the only atmosphere; no other CSS gradients exist on chrome.
- **Golden rule box** — a 3px `{colors.accent-yellow}` left border on a tile-1 box — is the single editorial accent in the hero.
- **Trail badges** encode gate state by color (green done with ✓, blue current, plain + % otherwise) — status as ambient decoration.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.none}` | 0px | Hero band, navs, footer, full-bleed tiles |
| `{rounded.xs}` | 4px | Trail badges, keycap |
| `{rounded.sm}` | 5px | Custom checkboxes |
| `{rounded.md}` | 8px | Criterion rows, project/vaga/dif boxes, text inputs, reset button |
| `{rounded.lg}` | 18px | Palette, gate, section, dif, and bar-row cards — the card signature |
| `{rounded.pill}` | 9999px | Primary/ghost buttons, search, evidence input, priority pills, practice tag, pill tabs, "don't" chips, streak pill |

Cards never go flat and never exceed 18px; anything that reads as an "action" is a full pill.

### Photography Geometry
There is no photography or product imagery. The only visuals are CSS-native: the hero glow wash, progress-bar fills, and the custom checkbox glyph (a 4×8px rotated white border-check on the CTA-blue fill).

## Components

> Each spec covers Default and Active/Pressed/Focus. Hover is documented only where it carries meaning (row highlight, button brighten).

### Navigation

**`global-nav`** — 44px sticky bar (`top: 0`, `z-index: 50`) on `{colors.canvas}` with a hairline bottom rule. Left: semibold 13px wordmark. Center: quiet 12px links (`{colors.mute}` → white on hover). Right: streak pill. At ≤1023px the link cluster hides; at ≤640px the whole bar goes `position: static` so only one sticky bar remains.

**`sub-nav-frosted`** — 52px frosted bar sticky below the global nav (`top: 44px`, `top: 0` at ≤640px). Left: gate-mini progress readout (`G2 — Gate de Estágio · 0%`); right: persistent small primary CTA ("Continuar") deep-linking to the current gate.

### Buttons

**`button-primary`** — Background `{colors.primary-focus}`, text `{colors.on-primary}` in `{typography.button}`, `{rounded.pill}`, padding 11px × 22px (≈44px tall). Hover brightens (`brightness(1.12)`); focus shows a 2px `{colors.primary}` outline; active fills `{colors.primary-pressed}` + `scale(0.95)` — the system-wide press micro-interaction.

**`button-small`** — Same grammar at `{typography.button-small}`, padding 8px × 16px. Used for sub-nav CTA and form submits.

**`button-ghost`** — Transparent with 1px `{colors.primary}` border and text, pill-shaped, same padding as primary. The "Ver critério" secondary action. Focus-visible gets the 2px focus-blue outline.

**`text-link`** — Inline prose links in `{colors.primary}`, no underline by default.

### Hero

**`hero-tile`** — Canvas band, padding 72px/56px, `overflow: hidden` (clips the glow; must never create page scroll).

**`hero-glow`** — The single decorative gradient (see Brand Gradient), `opacity: 0.28`, `pointer-events: none`, exactly 100% wide so its edges never exceed the tile.

**`palette-card`** + **`palette-card-shadow`** — tile-1 cards at `{rounded.lg}`/24px. The shadow variant adds the system's only drop-shadow and hosts the Objective + progress bars; the plain variant hosts the live next-blocker.

**`progress-bar-row`** — tile-1 rounded-18px row: 13px label + bold count on top, 8px track on `{colors.tile-3}` with hairline-soft inner border, fill in CTA blue / yellow (G2) / green (frontend).

**`steps-stepper`** — the career-hierarchy card: an ordered list, 14px rows separated by hairline rules, `→` markers (muted; blue for the current path, green for the optional Full-Stack trail), bold white stage names with muted detail spans. Stacks vertically at ≤640px. Replaced the old ASCII-art block that forced horizontal scrolling on mobile.

**`palette-search`** — 44px pill search on tile-2, 17px input, hairline border brightening to hairline-strong on focus-within. Live-filters every `li[data-text]` on the page; `/` and `⌘K` focus it.

**`keycap`** — 20px key glyph (tile-2 fill, hairline border, 4px radius). Hidden on touch devices (`hover: none`), where the hint is meaningless.

**`gate-trail-badge`** — 12px status chips: tile-3 + translucent-white text by default, green ring + ✓ when done, blue ring when current.

### Gates

**`gate-card`** — The working unit. tile-2 surface (tile-1 on tile-2 sections), `{rounded.lg}`, 24px padding. Header row: `G2 · Meta 90%` + `done/total · pct` meta. Status line in 13px semibold (red "Não pronto" / yellow "Pronto para avançar" / green "Gate concluído"). Thresholds: G0 80 · G1 80 · G2 90 · G3 85 · G4 80 · F1 70. A gate counts as done at 100% criteria, or at threshold **only with the project proven** (COMPROVADO + link).

**`criterion-row`** — 14px flex row, 8px padding, 10px gap, 8px radius, hover lifts to tile-3. Text column is `flex: 1` with `min-width: 0` + `overflow-wrap: anywhere` — the rule that keeps long criteria inside 390px viewports.

**`criterion-checkbox`** — 17px custom box: tile-3 fill, 1.5px hairline-strong ring, 5px radius; checked fills CTA blue with a white rotated-border check. Checking strikes the label through in stone. Focus-visible gets the 2px focus-blue outline.

**`prio-pill-core/comp/avanc/front`** — 11px semibold pills: CORE on red wash, COMP on yellow wash, AVANC on blue wash, FRONT on green wash. Priority is color + text, never color alone.

**`practice-tag`** — 11px dashed-yellow "conheço → praticar" tag on bootcamp-migrated items; clicking dismisses it (marks consolidated). Transparent background, pill-shaped.

**`project-box`** — Dashed hairline-strong box on tile-1: mandatory project title + evidence control.

**`pill-tab` / `pill-tab-active`** — Evidence ladder ESTUDADO → PRATICADO → APLICADO → COMPROVADO. Default transparent/body-text; active tile-3/white. Focus-visible outlined.

**`evidence-link-input`** — Full-width pill input for the proof link (commit/PR/API/deploy). No link + below-COMPROVADO = project doesn't count, and the gate header says so.

### Secondary Sections

**`section-card`** — Generic tile-2 rounded-18px container for candidatura, vaga registration, and informational notes.

**`dont-chip`** — Muted 13px pills listing explicit non-priorities (K8s, Kafka avançado, microservices…) — the roadmap's "no" list as a first-class component.

**`vaga-input` / `vaga-item`** — Market-feedback form (title/requirements/gaps) and its registered-vaga rows with a quiet remove button.

**`dif-card`** — Diferenciais category card: 15px semibold title + mini count, 11px uppercase stone fit-line ("encaixa bem: …"), criterion rows.

**`footer-band`** — Canvas footer, 12px muted: done-gates counter + danger-hover reset button, yellow storage warning, stone source line naming the repo's kept name (`roadmap-fullstack-java-junior`) for compatibility.

## Do's and Don'ts

### Do
- Keep the whole site in one continuous dark mode — `{colors.canvas}` edge to edge, tiles alternating down the ladder.
- Use `{colors.primary-focus}` (#0071e3) for primary button fills so white text holds 4.7:1; reserve bright `{colors.primary}` (#2997ff) for text accents, links, and glows.
- Enable the ss03 feature set on `body` — without it the type voice collapses to generic Inter.
- Encode priority only through `{component.prio-pill-core}` et al. — CORE red, COMP yellow, AVANC blue, FRONT green, always text + wash.
- Gate titles stay as `Gx · Meta N%` inside cards; full titles live only in section headlines.
- Size hero grids in `fr` units and give every flexible text column `min-width: 0` — `% + gap` and unwrappable pills caused the mobile overflow.
- Use `scale(0.95)` as the press state on every button.
- Keep the hero glow at 100% width inside an `overflow: hidden` hero — decoration must never create scroll width.

### Don't
- Don't put white text on `{colors.primary}` (#2997ff) — 3.02:1 fails AA for all text sizes.
- Don't use small text (`ash`/`stone`) below their fixed values — the originals failed at 3.75:1 and 2.03:1.
- Don't introduce a light mode, a second accent hue, or drop shadows on cards/buttons/text.
- Don't duplicate headlines between section head and card head.
- Don't document hover as a state — Default, Active/Pressed, and Focus-Visible only.
- Don't add new surface hexes — express elevation with the canvas → tile-1 → tile-2 → tile-3 ladder first.
- Don't let the stepper, trail, or glow reintroduce horizontal scroll — verify at 390px after every layout change.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Desktop | ≥ 1024px | Hero grid `2fr 3fr`; full dual sticky nav (44 + 52px); h1 56px, h2 40px |
| Stack | ≤ 1023px | Hero grid → 1 column; global-nav links hidden; tiles keep 80px padding |
| Phone | ≤ 640px | h1 34px, h2 28px; tile/hero padding 48px/16px; global nav static, sub-nav `top: 0`; steps stack vertical |
| Small phone | ≤ 419px | h1 28px; search input 15px |
| Touch | `hover: none` | Keycap hint hidden |
| Reduced motion | `prefers-reduced-motion` | Transitions off, smooth scroll off, hero glow hidden |

### Touch Targets
- `{component.button-primary}` lands at ≈44px tall — the AA floor. `{component.palette-search}` is 44px.
- `{component.pill-tab}` and `{component.practice-tag}` sit at ≈24–28px — compact by intent (segmented controls, not primary actions).
- `{component.criterion-checkbox}` is 17px with 8px row padding (≈33px effective row height) — below the 24px minimum; tracked in Known Gaps.

### Collapsing Strategy
- **Global nav:** full link row → links hidden at ≤1023px (wordmark + streak remain) → static (non-sticky) at ≤640px.
- **Sub-nav:** dual sticky → single sticky at ≤640px; CTA always visible.
- **Hero:** 2-column dashboard → 1-column stack at ≤1023px; glow stays clipped at every width.
- **Stepper:** horizontal baseline rows → vertical stack at ≤640px; no horizontal scroll at any width.
- **Section padding:** 80px → 48px at ≤640px; gutters 24px → 16px.

### Content Behavior
There is no image pipeline — the only "media" is CSS. Progress bars animate width (0.4s ease, disabled under reduced motion); the ⌘K filter hides non-matching `li[data-text]` without reflowing sections; gate renders are full re-renders from `localStorage` state on every toggle.

## Iteration Guide

1. Focus on ONE component at a time. Reference its entry directly (`{component.gate-card}`, `{colors.primary-focus}`) — never inline hex in new CSS.
2. New variants become separate entries (`-active`, `-focus`, per-priority pills) — never buried in prose.
3. After edits, verify: zero page-level overflow at 390px and 1280px, all small-text contrasts ≥ 4.5:1, no console errors, checkbox toggle still updates its dashboard counters.
4. Keep `{colors.primary-focus}` (CTA fill) scarce per viewport — at most one solid blue pill per fold; secondary actions use `{component.button-ghost}`.
5. When introducing a component, first try the surface ladder + 8/18px radii + existing accents before adding tokens. The system's strength is that it almost never needs new ones.
6. Data constants (`GATES`, `FRONT`, `CAND`, `DIF`) live in the `<script>` block of the same file — content edits and style edits ship together, in one commit.

## Known Gaps

- **Checkbox target size** — 17px boxes (≈33px rows) sit below the 24px minimum target; enlarging them without breaking the dense criterion scan is open work.
- **Form validation states** — vaga and evidence inputs have rest/focus only; no error, success, or disabled treatments are defined.
- **Dark mode is the only mode** — no light variant exists or is planned.
- **No visual regression tests** — verification is metric-based (overflow widths, contrast ratios, console errors via Playwright), not screenshot-based.
- **Trail badge `%` text** uses 12px translucent white that passes only by a small margin on tile-3; re-check if the badge surface ever changes.
- **Touch `⌘K` affordance** — with the keycap hidden on touch, there is no visible hint that `/` focuses search on mobile keyboards.
