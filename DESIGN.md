---
name: Lumina Slate
colors:
  surface: '#fbf8fe'
  surface-dim: '#dbd9df'
  surface-bright: '#fbf8fe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f2f8'
  surface-container: '#f0edf3'
  surface-container-high: '#eae7ed'
  surface-container-highest: '#e4e1e7'
  on-surface: '#1b1b1f'
  on-surface-variant: '#4a4455'
  inverse-surface: '#303034'
  inverse-on-surface: '#f2f0f5'
  outline: '#7b7487'
  outline-variant: '#ccc3d8'
  surface-tint: '#732ee4'
  primary: '#630ed4'
  on-primary: '#ffffff'
  primary-container: '#7c3aed'
  on-primary-container: '#ede0ff'
  inverse-primary: '#d2bbff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#5d25c7'
  on-tertiary: '#ffffff'
  tertiary-container: '#7645e0'
  on-tertiary-container: '#ece1ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#eaddff'
  primary-fixed-dim: '#d2bbff'
  on-primary-fixed: '#25005a'
  on-primary-fixed-variant: '#5a00c6'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#e9ddff'
  tertiary-fixed-dim: '#d0bcff'
  on-tertiary-fixed: '#23005c'
  on-tertiary-fixed-variant: '#5516be'
  background: '#fbf8fe'
  on-background: '#1b1b1f'
  surface-variant: '#e4e1e7'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: '1.15'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: '1.25'
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.65'
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.04em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: '1.6'
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

The design system establishes a focused, high-caliber identity for a student and aspiring software developer. It balances academic rigor, engineering precision, and creative curiosity. The interface projects quiet confidence, avoiding gimmicks in favor of structural clarity, immaculate typography, and refined micro-interactions.

The visual aesthetic synthesizes **Modern Corporate/SaaS** with an **Editorial Touch**:
- **Structured Canvas:** Anchored by a deep navy architectural rail/sidebar that grounds the viewport, paired with a luminous lavender-tinted stage for projects, writing, and code artifacts.
- **Atmospheric Warmth:** Soft lilac surfaces replace stark grays to lend an inviting, human touch to technical documentation and project showcases.
- **Tactile Refinement:** Smooth elevation transitions, delicate hairline borders, and pill-shaped interactive anchors deliver an intentional, deliberate tactile polish.

## Colors

The palette leverages high-contrast architectural framing paired with soft, comfortable reading surfaces:

- **Primary (`#7C3AED` - Royal Violet):** The interactive driver. Used for key callouts, active navigation indicators, inline links, and primary actions. Secondary states leverage `#8B5CF6` and `#A78BFA` for hover states, focus rings, and badge highlights.
- **Secondary (`#0F172A` - Midnight Slate):** The anchoring tone. Applied to persistent side navigation, high-contrast code snippets, and stark display headings.
- **Neutral Canvas (`#FAF7FD` / `#F3EEFA`):** The primary view surface. Replaces standard sterile white with a soft, warm lavender-tinted background that reduces glare and elevates purple accents.
- **Surface Tiers:**
  - `surface-base`: `#FAF7FD` (Main workspace canvas)
  - `surface-raised`: `#FFFFFF` (Cards, dialogs, floating panels)
  - `surface-sunken`: `#F3EEFA` (Input fields, code blocks, tab track backgrounds)
  - `surface-sidebar`: `#0F172A` (Sidebar background with `text-slate-100`)
- **Borders:** Thin structural strokes using `#E9DFF7` on light surfaces and `#1E293B` within the dark sidebar.

## Typography

The typography pairing unifies structural dynamism with uncompromised legibility:
- **Headlines & Labels (Plus Jakarta Sans):** Its geometric precision and contemporary rounded curves echo the pill shape language, providing strong character in large titles without sacrificing formality.
- **Body Text (Inter):** Highly legible across varied pixel densities, optimized for detailed descriptions of tech stacks, design decisions, and project summaries.
- **Code & Tech Specs (JetBrains Mono):** Monospaced utility for inline dependencies, Git branch badges, and syntax blocks.

## Layout & Spacing

The portfolio is structured around a dual-pane responsive layout:

- **Desktop (1024px+):** Fixed 280px left navigation rail (`#0F172A`) containing profile metadata, quick links, and core navigation. The right content canvas floats on `#FAF7FD` using a 12-column fluid grid capped at `1200px` max content width, centered with `margin-desktop`.
- **Tablet (768px - 1023px):** Compact 80px icon rail or collapsing off-canvas drawer. Main content collapses to an 8-column layout with `gutter: 1.5rem` and `margin-tablet: 2rem`.
- **Mobile (< 768px):** Single-column layout. The rail becomes a sleek, sticky bottom navigation or floating header. Content runs in a 4-column flow with `margin: 1rem`.

## Elevation & Depth

Visual hierarchy relies on quiet ambient depth rather than aggressive drop shadows:

- **Surface Layering:** Elements step forward through subtle value shifts from canvas (`#FAF7FD`) to card surface (`#FFFFFF`).
- **Ambient Shadow System:**
  - *Card Idle:* `0 1px 3px rgba(15, 23, 42, 0.04), 0 6px 16px -4px rgba(124, 58, 237, 0.04)`
  - *Card Hover:* `0 8px 24px -6px rgba(124, 58, 237, 0.12), 0 2px 6px rgba(15, 23, 42, 0.04)` with a translateY of `-2px`.
  - *Dropdown / Floating Overlay:* `0 12px 32px -4px rgba(15, 23, 42, 0.1), 0 4px 12px -2px rgba(124, 58, 237, 0.08)`.
- **Hairline Strokes:** Surfaces are framed with `1px solid #E9DFF7` (or `rgba(255, 255, 255, 0.08)` in dark zones) to retain edge definition across high-DPI displays.

## Shapes

The design system embraces a high-radius curve language that offsets the strict grid:
- **Interactive Elements (Buttons, Badges, Search Inputs):** Fully pill-shaped (`rounded-full` / 9999px) for an approachable, tactile identity.
- **Surface Containers (Cards, Modals):** Soft architectural boundary using `1.5rem` (`rounded-xl`), creating nested harmony with inner pill elements.
- **Embedded Tags & Code Insets:** `0.5rem` to retain structural alignment within dense technical specs.

## Components

### Buttons
- **Primary:** Full pill (`rounded-full`), background `#7C3AED`, label in white `Plus Jakarta Sans` semi-bold. On hover, background shifts to `#6D28D9` with smooth shadow diffusion.
- **Secondary/Outline:** Full pill, `1px solid #7C3AED`, transparent background, text `#7C3AED`. On hover, fills with `#F3EEFA`.
- **Dark Sidebar Action:** Subtle pill, surface `rgba(255, 255, 255, 0.08)`, border `1px solid rgba(255, 255, 255, 0.12)`, text white. Hover shifts to `rgba(124, 58, 237, 0.3)`.

### Project & Showcase Cards
- Crisp `#FFFFFF` card body with `1.5rem` border radius and `1px solid #E9DFF7` border.
- Features an image or live preview container with a clean `1rem` inset radius.
- Smooth scale-up and lift effect on hover (`transform: translateY(-3px)` with ambient purple-tinted shadow).

### Filter & Tech Stack Chips
- Compact pill height (28-32px), background `#F3EEFA`, border `1px solid #E9DFF7`, text `#0F172A` (or `#7C3AED` when active).
- Tech indicator variant contains a leading 6px colored dot representing status or language type.

### Input Fields
- Pill-shaped (`rounded-full`) or softened box (`rounded-xl` for multiline text areas).
- Background `#F3EEFA`, border `1px solid #E9DFF7`, text `#0F172A`. Focused state transitions border to `#7C3AED` with an outer glow `0 0 0 3px rgba(124, 58, 237, 0.15)`.

### Timeline / Experience Track
- Minimal continuous vertical hairline in `#E9DFF7` punctuated by `#7C3AED` circular nodes that expand into dual-ring halos for the current/most recent role.

### Code Display & GitHub Metrics
- Inset cards with `#0F172A` background, `JetBrains Mono` font, and syntax highlighting keyed to violet, emerald, and cyan. Header row includes repository details with active commit and star counters.