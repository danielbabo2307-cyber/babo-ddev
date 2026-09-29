---
name: Deep Tech Glass
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353943'
  surface-container-lowest: '#0a0e17'
  surface-container-low: '#181b25'
  surface-container: '#1c1f29'
  surface-container-high: '#262a34'
  surface-container-highest: '#31353f'
  on-surface: '#dfe2ef'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#dfe2ef'
  inverse-on-surface: '#2c303a'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#bdf4ff'
  on-secondary: '#00363d'
  secondary-container: '#00e3fd'
  on-secondary-container: '#00616d'
  tertiary: '#a4c9ff'
  on-tertiary: '#00315d'
  tertiary-container: '#4c93e7'
  on-tertiary-container: '#002a51'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#9cf0ff'
  secondary-fixed-dim: '#00daf3'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004f58'
  tertiary-fixed: '#d4e3ff'
  tertiary-fixed-dim: '#a4c9ff'
  on-tertiary-fixed: '#001c39'
  on-tertiary-fixed-variant: '#004883'
  background: '#0f131c'
  on-background: '#dfe2ef'
  surface-variant: '#31353f'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-code-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-code-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-action:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
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
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses high-calibre digital engineering, reliability, and precision tailored for a premium freelance tech brand operating from Abidjan. The visual identity merges an architectural deep-space atmosphere with tactile glassmorphism and surgical technical typography. 

The aesthetic is tailored to enterprise clients, ambitious startups, and international partners seeking elite full-stack web execution. It deliberately avoids generic dark mode templates in favor of layered obsidian depths, subtle luminous cyan halos, and translucent structural surfaces that signal meticulous craftsmanship, performance, and modern authority.

## Colors

The palette is engineered around dark light-absorption and controlled luminescence:
- **Base Canvas & Midnight Tiers**: Background foundations transition through `#090D16` (Deep Canvas), `#0D111D` (Surface Base), and `#111827` (Card / Elevated Substrates).
- **Primary & Accent Lights**: Electric Cobalt (`#3B82F6`) drives functional calls-to-action and active states, paired with an energized Cyan Glow (`#00E5FF`) dedicated to highlights, focus states, micro-badges, and code tokens. Light Cobalt (`#60A5FA`) acts as an interactive hover bridge and secondary detail tint.
- **Glass & Outlines**: Glass surfaces utilize `rgba(13, 17, 29, 0.7)` to `rgba(17, 24, 39, 0.65)` layered over subtle technical borders colored with `rgba(59, 130, 246, 0.15)` or `rgba(0, 229, 255, 0.12)`.
- **Text & Foreground Contrasts**: High-priority text sits at `#F8FAFC`, secondary details at `#94A3B8`, and subdued metadata at `#64748B`.

## Typography

Typography establishes an intentional contrast between structural human-centric presentation and technical code precision:
- **Headlines (Space Grotesk)**: Geometric, angled terminals evoke architectural precision and forward-looking momentum. Headings larger than 32px automatically scale via distinct mobile tokens (`headline-xl-mobile`, `headline-lg-mobile`) to prevent awkward line breaks on handheld viewports.
- **Body Text (Plus Jakarta Sans)**: Highly legible, balanced, and neutral, providing fatigue-free reading across project case studies, client breakdowns, and service descriptions.
- **Labels, Tags & Code (JetBrains Mono)**: Monospaced rigor for technology stacks, metrics, git tags, and terminal callouts. All monospaced metadata carries slightly tracked spacing (`letter-spacing: -0.01em`) for enhanced legibility against dark backgrounds.

## Layout & Spacing

The design system operates on an 8pt architectural rhythm anchored by a 12-column fluid grid on desktop (max canvas width: 1280px) and a single-column layout on mobile viewports:
- **Desktop (1024px+)**: 12 columns with `1.5rem` (24px) gutters and `3rem` (48px) safe margins. Case study sections, services, and statistics distribute across 4, 6, or 12 column cards.
- **Tablet (768px - 1023px)**: 8 columns with `1.25rem` (20px) gutters and `2rem` (32px) margins. Content rearranges from multi-column rows into balanced 2-column or stacked formations.
- **Mobile (< 768px)**: 4 columns or single-column stack with `1rem` (16px) gutters and `1.25rem` (20px) outer margins.
- **Background Tech Grid**: An ambient, low-opacity CSS grid (`line-width: 1px`, `rgba(59, 130, 246, 0.04)`, `48px x 48px` cell size) extends globally across the canvas, grounding elements in an authentic engineering environment.

## Elevation & Depth

Visual depth is produced by glassmorphism, progressive translucent stacking, and localized atmospheric glow:
- **Level 0 (Canvas)**: Background tint `#090D16` overlaid with the faint technical grid.
- **Level 1 (Panels & Shells)**: `background: rgba(13, 17, 29, 0.65)`, `backdrop-filter: blur(12px)`, edged with a razor-thin border `1px solid rgba(59, 130, 246, 0.12)`.
- **Level 2 (Cards & Active Modules)**: `background: rgba(17, 24, 39, 0.75)`, `backdrop-filter: blur(16px)`, bordered with `1px solid rgba(59, 130, 246, 0.22)`. Ambient drop shadow: `0 12px 32px -8px rgba(0, 0, 0, 0.5)`.
- **Level 3 (Modals & Overlays)**: `background: rgba(17, 24, 39, 0.9)`, `backdrop-filter: blur(24px)`, outlined with `1px solid rgba(0, 229, 255, 0.3)`. Drop shadow: `0 24px 48px -12px rgba(0, 0, 0, 0.7)`.
- **Glow Accents**: Primary interactive milestones and key project showcases project an ethereal background radial flare: `box-shadow: 0 0 35px -5px rgba(0, 229, 255, 0.2)`.

## Shapes

The interface balances sharp digital precision with ergonomic readability through a consistent roundedness level:
- Base controls, interactive chips, and input fields apply standard `0.5rem` (8px) rounding.
- Glassmorphic panels, portfolio cards, and modal windows scale up to `1rem` (16px) for softened, contemporary silhouettes.
- Interactive status pills, tag badges, and quick filters employ fully rounded pill geometry (`9999px`) to distinguish categorical metadata from primary structural cards.

## Components

- **Buttons**:
  - *Primary Action*: High-intensity electric blue fill (`#2563EB` to `#3B82F6`), high-contrast text (`#FFFFFF`), with an internal specular border highlight (`rgba(255, 255, 255, 0.18)`). On hover, manifests a vivid cyan peripheral glow (`box-shadow: 0 0 20px rgba(0, 229, 255, 0.4)`).
  - *Glass / Secondary*: Translucent panel fill (`rgba(17, 24, 39, 0.6)`), crisp perimeter border (`rgba(59, 130, 246, 0.25)`), text in `#F8FAFC`.
- **Chips & Tech Stack Badges**:
  - Rendered in `JetBrains Mono` at `12px`. Outlined in `rgba(0, 229, 255, 0.2)` with a tinted backdrop (`rgba(0, 229, 255, 0.05)`). Accompanied by micro green/cyan pulse dots for production readiness or framework indication.
- **Portfolio & Service Cards**:
  - Formed from Level 2 Glass containers. Interactive states trigger border transitions from subdued cobalt (`rgba(59, 130, 246, 0.15)`) to glowing cyan (`rgba(0, 229, 255, 0.45)`), accompanied by a subtle 4px vertical lift.
- **Inputs & Form Controls**:
  - Solid dark inset (`background: rgba(9, 13, 22, 0.8)`), inset hairline border (`rgba(59, 130, 246, 0.2)`), typography in `Plus Jakarta Sans`. Focus triggers an authoritative cyan ring (`border-color: #00E5FF`, `box-shadow: 0 0 12px rgba(0, 229, 255, 0.25)`).
- **Code Snippets & Terminal Viewers**:
  - Specialized components styled like dark CLI panes: top title-bar featuring status indicators (red/amber/green micro-dots), code display in `JetBrains Mono`, syntax highlights keyed strictly to `#00E5FF`, `#60A5FA`, and `#94A3B8`.