---
name: Kinetic Noir
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#1f1f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#bec7d4'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#88919d'
  outline-variant: '#3f4852'
  surface-tint: '#98cbff'
  primary: '#98cbff'
  on-primary: '#003354'
  primary-container: '#00a3ff'
  on-primary-container: '#00375a'
  inverse-primary: '#00629d'
  secondary: '#c8c6c8'
  on-secondary: '#303032'
  secondary-container: '#474649'
  on-secondary-container: '#b6b4b7'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#9c9d9d'
  on-tertiary-container: '#333535'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#cfe5ff'
  primary-fixed-dim: '#98cbff'
  on-primary-fixed: '#001d33'
  on-primary-fixed-variant: '#004a77'
  secondary-fixed: '#e4e2e4'
  secondary-fixed-dim: '#c8c6c8'
  on-secondary-fixed: '#1b1b1d'
  on-secondary-fixed-variant: '#474649'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
  electric-blue-glow: rgba(0, 163, 255, 0.4)
  charcoal-surface: '#121212'
  glass-stroke: rgba(255, 255, 255, 0.15)
typography:
  display-lg:
    fontFamily: anybody
    fontSize: 80px
    fontWeight: '800'
    lineHeight: 88px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: anybody
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: anybody
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: 0.02em
  body-lg:
    fontFamily: hankenGrotesk
    fontSize: 18px
    fontWeight: '300'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: hankenGrotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: jetbrainsMono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.15em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  margin-desktop: 80px
  margin-mobile: 24px
  gutter: 24px
  section-gap: 160px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system embodies a **Cinematic, Futuristic, and Minimalist** aesthetic tailored for high-end athletic performance. It is designed to evoke a sense of velocity, exclusivity, and technological precision. The experience is defined by high-contrast environments where the product is treated as a piece of sculpture, emerging from deep shadows into "electric" light.

The style leverages **Glassmorphism** and **Subtle Glows** to create depth within a dark-mode-first architecture. It borrows the structural rigor of premium technology brands and the aggressive, forward-leaning energy of elite sports marketing. The interface should feel like a high-tech HUD (Heads-Up Display) overlaying a high-fidelity cinematic capture of the product.

## Colors

The palette is anchored in **Pure Black (#000000)** to ensure maximum OLED depth and an infinite canvas feel. 

- **Primary:** Electric Blue (#00A3FF) is used sparingly as a "lighting" element—simulating LEDs, laser-thin strokes, or interactive states.
- **Surface:** Deep Charcoal (#1D1D1F and #121212) provides the base for containers, creating a subtle tiered hierarchy against the pure black background.
- **Typography:** Crisp White (#FFFFFF) is the primary engine for legibility, providing a stark, premium contrast.
- **Accents:** Use low-opacity glow effects (`electric-blue-glow`) behind primary calls-to-action to simulate a physical light source emanating from the UI.

## Typography

The typography strategy focuses on the juxtaposition of power and precision. 

- **Headlines:** Use **Anybody** (or a similar wide, bold sans-serif). Its expansive width suggests speed and stability. Use tight tracking for large displays to create a "blocky" cinematic feel.
- **Body:** Use **Hanken Grotesk** at a light weight (300). The generous x-height and clean geometry provide a sophisticated contrast to the aggressive headlines.
- **Technical Labels:** Use **JetBrains Mono** for technical specs and leader-line callouts. This monospaced choice reinforces the "futuristic tech" narrative of the shoe's construction.

## Layout & Spacing

This design system utilizes a **Fluid Grid** with generous vertical breathing room to mimic high-fashion editorial layouts.

- **Desktop:** A 12-column grid with 80px side margins. Large-scale imagery should often break the grid or bleed off-edge to create a sense of scale.
- **Section Gaps:** Use an aggressive 160px vertical gap between major content blocks to ensure each "feature" of the shoe is treated as an isolated exhibit.
- **Reflow:** On mobile, margins shrink to 24px, and typography should scale aggressively (using `display-lg-mobile`) to maintain the high-impact visual hierarchy.

## Elevation & Depth

Depth is conveyed through **Glassmorphism and Tonal Layering** rather than traditional shadows.

- **The Z-Axis:** Elements closest to the user (like navigation and modals) use a semi-transparent background (approx. 40% opacity) with a high-density `backdrop-filter: blur(20px)`.
- **Glows:** Instead of drop shadows, use "Outer Glows" for active elements. These should be 0px offset, using the Primary Electric Blue at low opacity to suggest the element is luminescent.
- **Strokes:** Use 1px "Ghost Borders"—low-opacity white or blue lines—to define edges on dark surfaces without adding visual bulk.

## Shapes

The shape language is dominated by the **Pill** and the **Sharp Edge**. 

Interactive elements like buttons and chips use a maximum roundedness (Pill-shaped) to provide a sleek, aerodynamic feel that mimics the curves of premium footwear. In contrast, layout containers and image masks should remain sharp or have minimal rounding to maintain a sophisticated, architectural edge.

## Components

### Buttons
- **Primary:** Pill-shaped, Primary Electric Blue background with a subtle top-to-bottom gradient. Text is Bold Mono in Black.
- **Secondary:** Transparent pill with a 1px Primary Blue border and a subtle hover glow.

### Navigation
- **Header:** Fully transparent background that blurs content underneath as the user scrolls. Minimalist text links in `label-caps`.

### Premium Callouts
- **Leader Lines:** 0.5px thickness crisp white lines connecting a technical label (monospaced) to a specific point on the shoe. The line should end in a small 4px solid circle.

### Cards & Surfaces
- Surfaces should use the **Deep Charcoal** hex with a 1px `glass-stroke` at 10% opacity. No heavy drop shadows; let the color difference and the subtle border define the boundary.

### Inputs & Selection
- **Inputs:** Bottom-border only or very subtle ghost-outlines. 
- **Checkboxes/Radio:** Circular/Pill-based to match the button language, utilizing the Electric Blue for the active state.