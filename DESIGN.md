---
name: Lush Tropical Modernism
colors:
  surface: '#f9f9fc'
  surface-dim: '#dadadc'
  surface-bright: '#f9f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f6'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e5'
  on-surface: '#1a1c1e'
  on-surface-variant: '#424750'
  inverse-surface: '#2f3133'
  inverse-on-surface: '#f0f0f3'
  outline: '#727781'
  outline-variant: '#c2c6d1'
  surface-tint: '#27609d'
  primary: '#003461'
  on-primary: '#ffffff'
  primary-container: '#004b87'
  on-primary-container: '#8abcff'
  inverse-primary: '#a3c9ff'
  secondary: '#006d43'
  on-secondary: '#ffffff'
  secondary-container: '#75f8b3'
  on-secondary-container: '#007147'
  tertiary: '#2c3439'
  on-tertiary: '#ffffff'
  tertiary-container: '#424b50'
  on-tertiary-container: '#b2bbc0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3e4ff'
  primary-fixed-dim: '#a3c9ff'
  on-primary-fixed: '#001c38'
  on-primary-fixed-variant: '#004882'
  secondary-fixed: '#78fbb6'
  secondary-fixed-dim: '#59de9b'
  on-secondary-fixed: '#002111'
  on-secondary-fixed-variant: '#005232'
  tertiary-fixed: '#dbe4ea'
  tertiary-fixed-dim: '#bfc8ce'
  on-tertiary-fixed: '#141d21'
  on-tertiary-fixed-variant: '#3f484d'
  background: '#f9f9fc'
  on-background: '#1a1c1e'
  surface-variant: '#e2e2e5'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

The brand identity centers on the intersection of Sri Lanka's raw natural beauty and a sophisticated, premium beverage experience. This design system evokes a sense of "elevated refreshment"—it is cool to the touch, vibrant in spirit, and meticulously clean in execution. 

The aesthetic is **Modern Minimalist** with **Glassmorphism** accents. We use expansive whitespace to allow high-resolution product photography to breathe, mimicking the clarity of fresh water. Visual elements should feel light and airy, utilizing subtle transparency to suggest condensation and coolness. The emotional response is one of rejuvenation, trust, and high-end quality.

## Colors

This design system utilizes a palette inspired by the Sri Lankan landscape: a deep, authoritative **Deep Sea Blue** for trust and heritage, paired with a vibrant **Ceylon Green** to represent natural freshness and vitality. 

- **Primary (Deep Sea Blue):** Used for core branding, primary buttons, and deep backgrounds.
- **Secondary (Ceylon Green):** Used as an accent for "fresh" callouts, health indicators, and active states.
- **Tertiary (Mist Blue):** A very faint, cool-toned wash used for section backgrounds and soft containers to maintain a "chilled" feeling.
- **Neutral:** A rich charcoal-black is used for maximum legibility in typography, avoiding pure black to maintain a premium, softer edge.

## Typography

The typography strategy pairs **Plus Jakarta Sans** for headlines with **Hanken Grotesk** for body and functional text. 

Plus Jakarta Sans provides a friendly yet professional geometric structure that feels contemporary and approachable. Its open apertures work beautifully for high-impact display text. Hanken Grotesk offers a sharper, more technical precision for body copy, ensuring that nutritional information and product descriptions feel "lab-grade" and trustworthy. 

We utilize tighter letter-spacing on display sizes to create a "contained" premium look, while increasing tracking on labels for better legibility at small sizes.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** model with generous margins to enforce a feeling of "luxury and space." 

- **Desktop:** A 12-column grid with 24px gutters. Use 80px or 120px vertical padding between major sections to emphasize the minimalist aesthetic.
- **Mobile:** A 4-column grid with 16px margins. Content should be stacked vertically with ample breathing room (at least 48px) between distinct product modules.
- **Rhythm:** All spacing must be a multiple of the 8px base unit. 

Emphasis is placed on asymmetric layouts where imagery overlaps container boundaries, creating a dynamic, "organic" flow rather than a rigid, boxed-in corporate feel.

## Elevation & Depth

To maintain a "refreshing" and "light" feel, this design system avoids heavy, muddy shadows. Depth is communicated through:

1.  **Glassmorphism (Primary Depth):** Containers use a semi-transparent background (e.g., `rgba(255, 255, 255, 0.7)`) with a high `backdrop-filter: blur(20px)`. This creates a frosted-glass effect, mimicking cold beverage packaging.
2.  **Tonal Layering:** Surfaces are built using subtle shifts in the Tertiary (Mist Blue) color rather than shadows.
3.  **Ambient Glows:** For primary actions, use a soft, colored outer glow in the primary blue or secondary green (low opacity, large spread) to simulate light passing through liquid.
4.  **Floating Elements:** Product hero images should use high-quality cutouts with soft, directional contact shadows to appear as if they are floating in an airy, brightly lit space.

## Shapes

The shape language is **Rounded**, reflecting the soft curves of water droplets and organic forms. 

Standard components (buttons, input fields) use a 0.5rem (8px) radius. Larger cards and product containers use 1.5rem (24px) to feel more "friendly" and modern. We avoid sharp 90-degree corners to ensure the UI feels approachable and soft, mirroring the natural ingredients of the beverages. Iconic shapes—like the "circle" of a bottle cap—should be echoed in secondary elements like image frames or iconography backgrounds.

## Components

- **Buttons:** Primary buttons are solid Deep Sea Blue with white text and a subtle 8px radius. Secondary buttons should use the "Glass" effect: transparent with a thin white border and backdrop blur.
- **Chips:** Used for flavors or ingredients (e.g., "Lime," "Natural Sugar"). These should be Ceylon Green with low-opacity backgrounds and high-contrast text.
- **Input Fields:** Minimalist design with only a bottom border that thickens and turns Deep Sea Blue on focus. Labels should be small and uppercase.
- **Cards:** Product cards must use the Glassmorphism style. They should feature a large product image that "breaks" the top edge of the card, creating a 3D effect.
- **Imagery:** All imagery must be high-key (brightly lit), featuring macro shots of water droplets, fresh fruit, or lush Sri Lankan tea leaves. 
- **Navigation:** A sticky top-bar using a heavy backdrop blur so it feels like a sheet of ice moving over the content.