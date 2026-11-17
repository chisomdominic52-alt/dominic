---
name: Obsidian Kinetic
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#c0c1ff'
  on-secondary: '#1000a9'
  secondary-container: '#3131c0'
  on-secondary-container: '#b0b2ff'
  tertiary: '#d8ffe7'
  on-tertiary: '#003824'
  tertiary-container: '#65f2b5'
  on-tertiary-container: '#006d4a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#e1e0ff'
  secondary-fixed-dim: '#c0c1ff'
  on-secondary-fixed: '#07006c'
  on-secondary-fixed-variant: '#2f2ebe'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.75rem
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.5rem
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: '1.25'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.7'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  code-badge:
    fontFamily: JetBrains Mono
    fontSize: 0.8125rem
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses a high-caliber technical narrative tailored for an accomplished software engineer. It projects intellectual rigor, architectural precision, and refined modern craftsmanship. The aesthetic merges precision engineering with fluid kinetic energy, framing technical proficiency across legacy foundations and modern front-end technologies with equal dignity.

The design movement blends **Modern Dark-Mode Minimalism** with **Luminous Glassmorphic Accents**. Visual weight is achieved through deep, obsidian surfaces, pin-sharp micro-borders, and targeted kinetic glows that suggest live computation. The emotional takeaway is that of an authoritative, dependable builder who balances rock-solid backend logic with modern, high-polish interfaces.

## Colors

The core palette operates around a deep structural substrate illuminated by hyper-vibrant signal accents:

- **Primary (`#00F0FF` - Luminous Cyan):** Used for focal points, interactive key actions, glowing borders, active navigation states, and link hover states.
- **Secondary (`#6366F1` - Electric Indigo):** Anchors deep tech elements, gradients, secondary highlights, timeline nodes, and background ambient dispersion fields.
- **Tertiary (`#10B981` - Emerald Accent):** Denotes operational readiness, active service states, production metrics, terminal prompts, and verification badges.
- **Neutral (`#0F172A` - Obsidian Slate):** Defines base layered canvases, surface tiers, and text contrast hierarchies.

### Surface Tiers & Modes
- **Dark Mode (Default):** Canvas sits at `#090D16` with elevated cards layering to `#0F172A` and floating dialogs at `#1E293B`. Borders use `#334155` at 40% to 60% opacity.
- **Light Mode:** Canvas shifts to `#F8FAFC`, with elevated containers at `#FFFFFF` and borders resting at `#E2E8F0`. Primary cyan deepens to high-contrast `#007A87` to maintain WCAG AAA compliance, while indigo shifts to `#4F46E5`.

## Typography

The typographical structure utilizes a triad system to delineate roles:

1. **Plus Jakarta Sans** commands headlines and titles, offering geometric precision softened by contemporary editorial warmth. Tight tracking on display headers delivers a cohesive, bespoke visual impact.
2. **Inter** drives all narrative and structural body content, selected for its unmatched readability, extensive weight range, and neutral digital clarity.
3. **JetBrains Mono** is reserved strictly for technical metadata, execution stats, file architecture trees, commit tags, and language stack badges (PHP, JS, CSS, etc.). It establishes explicit code-centric authenticity.

## Layout & Spacing

This design system uses a strict 12-column responsive fluid grid structured with an 8px rhythmic sub-grid:

- **Desktop (1280px+):** 12 columns, max-width bounded at 1200px (or 1440px for broad hero/showcases), centered with 32px (`margin`) outer gutters and 24px (`gutter`) column spacing.
- **Tablet (768px – 1024px):** 8 columns, 24px outer margins, 20px gutters. Dual-pane portfolio cards reflow into structured vertical stacks or 2-column groupings.
- **Mobile (< 768px):** 4 columns, 20px outer margins (`margin-mobile`), 16px gutters (`gutter-mobile`). Visual metrics switch from side-by-side matrices into full-width horizontal-scroll strips or single-column lists.

Vertical rhythm is governed by `space-xl` for section separation, `space-lg` between distinct content blocks, and `space-md` within card containers.

## Elevation & Depth

Visual hierarchy leverages a hybrid of **Tonal Layering** and **Luminous Edge Deflection**:

- **Layer 0 (Canvas):** Pure dark background (`#090D16`) with an optional low-opacity SVG matrix or faint radial grid pattern.
- **Layer 1 (Card & Content Blocks):** Obsidian Slate (`#0F172A`) at 85% opacity with an active `backdrop-filter: blur(12px)`. Enclosed by a 1px boundary line (`rgba(255, 255, 255, 0.08)` in dark mode; `rgba(15, 23, 42, 0.08)` in light mode).
- **Layer 2 (Hover & Focus States):** Subtle vertical lift (`transform: translateY(-2px)`). The card outline is augmented by a concentrated cyan/indigo rim highlight: `box-shadow: 0 0 20px -5px rgba(0, 240, 255, 0.25), 0 8px 16px -4px rgba(0, 0, 0, 0.4)`.
- **Layer 3 (Overlays, Drawers & Modals):** Surface elevation `#1E293B`, reinforced by deep ambient drop shadows (`box-shadow: 0 24px 48px -12px rgba(0, 0, 0, 0.6)`) and a darkened, blurred backdrop overlay (`rgba(9, 13, 22, 0.75)`).

## Shapes

The design system enforces a balanced geometric form factor (`roundedness: 2`).

- **Standard Containers & Cards:** Base corner radius is `0.5rem` (8px). Large showcase project containers and hero summary modules adopt `rounded-lg` (`1rem` / 16px).
- **Interactive Atoms (Buttons & Input Fields):** Standardized at `0.5rem` (8px) to retain technical sharpness without aggressive harshness.
- **Pills & Metatags:** Stack indicators, availability signals, and terminal tags utilize full-radius pills (`rounded-full` / 9999px) to contrast structurally against square project panels.

## Components

### Buttons
- **Primary:** Gradient fill transitioning from Cyan (`#00F0FF`) to Indigo (`#6366F1`) with bold dark slate text (`#090D16`). On hover, an outer neon diffusion glow ignites (`0 0 24px rgba(0, 240, 255, 0.4)`).
- **Secondary (Ghost Outline):** Transparent background with a 1px subtle white/border line (`rgba(255, 255, 255, 0.15)`), shifting on hover to solid `#0F172A` with a cyan-tinted border and text.
- **Icon Actions:** Monospaced 1:1 ratio blocks featuring SVG icons, encased in low-contrast borders with a subtle glass backdrop.

### Chips & Badges
- **Tech Stack Badges:** Rendered using `label_font` (`JetBrains Mono`). Slate background (`rgba(15, 23, 42, 0.6)`), 1px border (`rgba(255, 255, 255, 0.1)`), paired with a colored language indicator (e.g., Indigo dot for PHP, Yellow for JS, Cyan for CSS/Bootstrap).
- **Status Indicator:** Pill format holding an animated pulsating dot (Emerald `#10B981`) denoting "Open to select roles / contracts".

### Cards (Project & Experience)
- Constructed with backdrop blur and low-contrast perimeter borders.
- Top section holds an optional project thumbnail or responsive browser mock-frame; body contains bold typography, descriptive summary, and a stack badge cluster.
- Integrated pseudo-element dynamic lighting: a subtle hover-tracked radial glow responds to cursor placement along the border edge.

### Input Fields & Contact Modules
- Background fill matches Layer 1 slate. 1px low-opacity border.
- On focus, smooth transition to an electric cyan stroke with an accompanying ambient glow ring (`0 0 0 3px rgba(0, 240, 255, 0.2)`).
- Placeholder labels use muted monochrome tones with absolute alignment.

### Code Snippets & Terminal Showcase
- Styled like an IDE / console container with macOS-style window action dots (red, yellow, green) on the top bar.
- JetBrains Mono syntax-highlighted code output illustrating clean architecture in PHP/JavaScript, complete with line numbers and a 1-click clipboard copy utility.