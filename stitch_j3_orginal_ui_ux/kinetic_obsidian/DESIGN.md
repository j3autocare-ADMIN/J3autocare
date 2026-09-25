---
name: Kinetic Obsidian
colors:
  surface: '#16130a'
  surface-dim: '#16130a'
  surface-bright: '#3c392e'
  surface-container-lowest: '#100e06'
  surface-container-low: '#1e1c12'
  surface-container: '#222016'
  surface-container-high: '#2d2a1f'
  surface-container-highest: '#38352a'
  on-surface: '#e9e2d2'
  on-surface-variant: '#cec6ad'
  inverse-surface: '#e9e2d2'
  inverse-on-surface: '#333026'
  outline: '#97917a'
  outline-variant: '#4b4734'
  surface-tint: '#e2c62d'
  primary: '#fffcff'
  on-primary: '#393000'
  primary-container: '#fde047'
  on-primary-container: '#726300'
  inverse-primary: '#6d5e00'
  secondary: '#c9c6c5'
  on-secondary: '#313030'
  secondary-container: '#474646'
  on-secondary-container: '#b7b4b4'
  tertiary: '#f9feff'
  on-tertiary: '#313030'
  tertiary-container: '#e3e0df'
  on-tertiary-container: '#646363'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe24c'
  primary-fixed-dim: '#e2c62d'
  on-primary-fixed: '#211b00'
  on-primary-fixed-variant: '#524600'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c9c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#16130a'
  on-background: '#e9e2d2'
  surface-variant: '#38352a'
  electric-yellow: '#FDE047'
  void-black: '#050505'
  charcoal-surface: '#1A1A1A'
  glass-border: rgba(253, 224, 71, 0.2)
  text-dim: '#A1A1AA'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.1em
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.2em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 128px
---

## Brand & Style

The design system is a premium, high-performance visual framework tailored for the automotive technology sector. It evokes the feeling of a futuristic vehicle dashboard—precise, cinematic, and authoritative. The aesthetic balances deep, "true black" foundations with high-energy accents and technical translucency.

The brand personality is **Elite, Engineering-Led, and Precision-Focused**. It targets high-end automotive enthusiasts and professionals who value technical superiority and aesthetic minimalism.

### Visual Style: Tech-Noir Glassmorphism
The system utilizes a refined mix of **Minimalism** and **Glassmorphism**. Key characteristics include:
- **Cinematic Depth:** Deep black backgrounds serve as a void for luminous technical elements.
- **Micro-Technical Details:** Usage of ultra-thin borders (0.5px to 1px) to simulate precision-machined edges.
- **Luminous Interaction:** Interactive elements emit a subtle glow, referencing automotive HUDs (Heads-Up Displays).
- **Industrial Refinement:** Large typography and generous whitespace ensure the UI feels expansive and premium.

## Colors

This design system is strictly **Dark Mode**. The palette is designed to maximize contrast and focus on the primary action color.

- **Primary (Electric Yellow):** Reserved for critical actions, the "J3" logo identity, and high-priority status indicators. It represents energy and precision.
- **Secondary (Void Black):** The canvas. This deep black provides the "cinematic" feel and allows other colors to pop without visual noise.
- **Tertiary (Charcoal):** Used for structural surfaces, cards, and subtle background differentiation.
- **Accent Details:** Semi-transparent versions of the primary yellow are used for borders and "luminous" glass effects to create depth without overwhelming the eye.

## Typography

The typography strategy emphasizes **technical precision**. 

- **Inter** is the primary typeface for all headings and body copy, chosen for its modern, clean, and highly legible characteristics.
- **JetBrains Mono** is introduced for labels, data points, and technical specifications, reinforcing the "automotive engineering" narrative.
- **Styling Rules:** Large display headings should use heavy weights with tight tracking. Technical labels should always be uppercase with increased letter spacing to emulate industrial markings.

## Layout & Spacing

The layout utilizes a **Fixed Grid** model on desktop and a **Fluid Grid** on mobile.

- **Desktop:** A 12-column grid with a max-width of 1440px. Gutters are kept at 24px to maintain a compact, "instrument panel" feel.
- **Rhythm:** Spacing follows an 8px base unit. 
- **Breathing Room:** While the elements themselves are technical and dense, the layout utilizes large section gaps (128px+) to maintain a high-end, gallery-like feel. 
- **Reflow:** On mobile, margins reduce to 16px, and complex technical grids collapse into a single-column stack, prioritizing legibility and thumb-driven interaction.

## Elevation & Depth

This design system avoids traditional drop shadows in favor of **Tonal Layering** and **Luminous Glassmorphism**.

- **Base Layer:** Pure #050505 background.
- **Surface Layer:** #1A1A1A with a 1px border of `rgba(255, 255, 255, 0.05)`.
- **Active Glass:** Surfaces use `backdrop-filter: blur(20px)` with a semi-transparent primary yellow border at 15% opacity.
- **Luminescence:** High-elevation elements (like primary buttons or active cards) use a soft yellow outer glow (`box-shadow: 0 0 25px rgba(253, 224, 71, 0.15)`) instead of a dark shadow.

## Shapes

The shape language reflects modern automotive design—aerodynamic but structured. 

- **Standard Radius:** 8px (`rounded`) for buttons and small inputs.
- **Container Radius:** 16px (`rounded-lg`) for cards and modal overlays.
- **Interaction:** Avoid pill-shapes for primary buttons to keep the "technical" aesthetic; use the 8px rounded corners for a more structural, stable appearance.

## Components

### Buttons
- **Primary:** Solid #FDE047 fill with #050505 text. No border. On hover, add a subtle yellow glow.
- **Secondary:** Ghost style. 1px border of #FDE047 with #FDE047 text. Background is transparent.
- **Technical:** All buttons should use the `label-caps` typography style.

### Cards
- **Construction:** Use #1A1A1A as the background. 
- **Border:** Use a 1px "machined" border (`rgba(255, 255, 255, 0.1)`). 
- **Header:** Include a JetBrains Mono label in the top-left corner for a "serial number" or technical descriptor effect.

### Input Fields
- **Default:** Dark background (#050505), 1px subtle gray border.
- **Focus:** Border transitions to #FDE047 with a faint yellow inner-glow. Label moves above the field in `label-caps` styling.

### Chips & Tags
- **Style:** Small, rectangular with 4px radius. Use JetBrains Mono.
- **Usage:** Indicate service categories (e.g., "CERAMIC COATING", "DETAILING") using high-contrast yellow text on a 10% opacity yellow background.

### Navigation
- **Top Bar:** 70% transparent Void Black with `backdrop-filter: blur(12px)`. Bottom border only, 1px thickness.