---
name: Academic Minimalist
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#3f4850'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#707881'
  outline-variant: '#bfc7d2'
  surface-tint: '#006398'
  primary: '#006194'
  on-primary: '#ffffff'
  primary-container: '#007bb9'
  on-primary-container: '#fdfcff'
  inverse-primary: '#93ccff'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#5cfae7'
  on-secondary-container: '#007167'
  tertiary: '#7d5400'
  on-tertiary: '#ffffff'
  tertiary-container: '#9e6a00'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cce5ff'
  primary-fixed-dim: '#93ccff'
  on-primary-fixed: '#001d31'
  on-primary-fixed-variant: '#004b73'
  secondary-fixed: '#5cfae7'
  secondary-fixed-dim: '#33ddcb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#ffddb1'
  tertiary-fixed-dim: '#ffba49'
  on-tertiary-fixed: '#291800'
  on-tertiary-fixed-variant: '#614000'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
  surface-canvas: '#F8FAFC'
  surface-card: '#FFFFFF'
  border-subtle: '#E2E8F0'
  text-muted: '#64748B'
  badge-sky-bg: '#E0F2FE'
  badge-teal-bg: '#CCFBF1'
  scholar-blue: '#0077B5'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 1.5rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system establishes an airy, human-centered, and approachable aesthetic tailored for early-career researchers, doctoral candidates, and interdisciplinary academics. Rather than adopting the dense, institutional rigidity of legacy academic portals, it merges Scandinavian minimalism with modern editorial clarity.

The interface prioritizes reading comfort, intellectual vitality, and accessible scholarship. Visual weight is carried primarily through generous whitespace, precise typographic scales, and purposeful accent moments. The emotional tone is welcoming yet rigorous: authoritative enough for fellowship committees and hiring panels, yet personal and friendly enough to invite student mentorship and research collaborations.

## Colors

The palette is engineered around clean white card planes elevated against a subtle cool-slate canvas (`#F8FAFC`). 

- **Primary (`#0284C7`)**: An energetic, scholarly sky cobalt used for primary focal points, active navigation links, publication download triggers, and hyperlinked titles.
- **Secondary (`#00CCBB`)**: A fresh cyan-teal used sparingly for active status indicators, collaborative project badges, and secondary highlight tags.
- **Tertiary (`#EAA428`)**: A warm amber utilized for research awards, conference honors, and "forthcoming" publication markers.
- **Neutral (`#1E293B`)**: A deep slate gray that replaces stark `#000000` to eliminate eye fatigue during long reading sessions while maintaining WCAG AAA contrast ratios against white surfaces.

Muted slate (`#64748B`) handles metadata, co-author lists, conference venues, and timestamps.

## Typography

Typography pairs **Plus Jakarta Sans** for structural titles and interface affordances with **Inter** for long-form narrative body and publication abstracts. 

- **Headlines & Display**: Plus Jakarta Sans provides contemporary geometric geometry tempered with humanist curves, softening traditional academic severity.
- **Body Text**: Inter provides uniform optical tracking and robust vertical metrics, preserving reading legibility across multi-paragraph bios, abstract dropdowns, and CV entries.
- **Hierarchy Rules**: The bio lead paragraph uses `body-lg` at 18px with relaxed line height (30px) for effortless scanning. Section headers employ tight negative tracking to maintain crisp visual density.

## Layout & Spacing

Layout adheres to a single-column constrained system within a maximum content boundary of `880px` for text-heavy academic pages, expanding to `1080px` for dual-column project or publication lists.

- **Vertical Rhythm**: Generous vertical spacing (`space-2xl` / 64px) separates major sections (e.g., Selected Publications, Teaching, News, Advising) to prevent information density overload.
- **Header Alignment**: The introductory hero utilizes an asymmetrical horizontal row: an 80px to 110px circular portrait anchored alongside the intro narrative, reflowing to a centered vertical stack below `640px`.
- **Breakpoints**: Mobile (< 640px), Tablet (640px–1023px), and Desktop (≥ 1024px). Horizontal canvas margins dynamically scale from `1.5rem` on mobile screens to `3rem` on desktop displays.

## Elevation & Depth

Visual depth is achieved through delicate surface containment rather than heavy drop shadows:

- **Flat Layering**: The primary canvas rests on `#F8FAFC`. Content cards, paper entries, and interactive widgets sit on crisp `#FFFFFF` with a single 1px hairline border in `#E2E8F0`.
- **Micro-Shadows**: Floating elements (such as sticky navigation bars and modal abstracts) leverage a subtle atmospheric shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.05)`.
- **Hover Transitions**: Interactive publication rows and button targets translate upward by -1px accompanied by a soft halo (`0 6px 16px -4px rgba(2, 132, 199, 0.08)`), signaling tactile reactivity without visual clutter.

## Shapes

The design system maintains a balanced **Rounded (`roundedness: 2`)** geometry:
- Standard UI containers, cards, and input fields utilize `8px` (`0.5rem`) corner radii.
- Interactive tags, filter pills, badge callouts, and profile avatars utilize full circular radii (`9999px`) to reinforce warmth and accessibility.
- Button components follow consistent `6px` to `8px` rounded corners, matching the container architecture.

## Components

### Buttons
- **Primary Button**: Solid fill in `#0284C7` with `#FFFFFF` text, `0.5rem` radius, horizontal padding of `1.25rem`, vertical padding of `0.625rem`. Used for primary actions like "Download CV" or "Email Me". Hover state transitions to `#0369A1`.
- **Secondary / Outline Button**: Hairline border (`1px solid #E2E8F0`), `#1E293B` text, `#FFFFFF` background. Hover shifts border color to `#0284C7` and text to `#0284C7`.
- **Icon Buttons**: Circular or squircle padded buttons (`36px × 36px`) for academic social links (Google Scholar, GitHub, ORCID, LinkedIn), tinted with `#64748B` and transitioning to `#0284C7` on hover.

### Chips & Badges
- **Status Pills**: Pill-shaped (`rounded-full`) tags displaying topics (e.g., "HCI", "LLMs", "Accessibility"). Default background `#F1F5F9` with `#475569` text.
- **Award Badges**: Background `#FEF3C7` with `#92400E` text and a subtle star/award icon indicator.
- **Publication Venue Tags**: Compact text labels using `label-sm` rendered in `#0284C7` over `#E0F2FE` background.

### Publication Cards & List Items
- Structured as clean horizontal rows or distinct modular cards:
  - **Title**: Semibold, linked with subtle color change to primary blue on hover.
  - **Author List**: Muted slate (`#64748B`), bolding candidate's name (e.g., **Elena Rostova**) for quick CV tracking.
  - **Venue & Year**: Italicized or tagged pill (e.g., *CHI 2025* or *NeurIPS 2024*).
  - **Inline Action Links**: Text links with micro-pill borders: `[PDF]`, `[Code]`, `[BibTeX]`, `[Project Page]`.

### Navigation Bar
- A lightweight, floating or fixed top bar (`64px` height) with backdrop blur (`backdrop-blur-md` over `rgba(255, 255, 255, 0.85)`) and a delicate bottom border (`1px solid #E2E8F0`). 
- Candidate name on the left in `headline-sm`, clean text links (About, Research, Publications, Teaching, CV) spaced `1.5rem` apart on the right.