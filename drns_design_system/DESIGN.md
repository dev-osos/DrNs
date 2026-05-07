---
name: DrNs Design System
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#43474c'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#74777d'
  outline-variant: '#c4c6cd'
  surface-tint: '#4e6073'
  primary: '#162839'
  on-primary: '#ffffff'
  primary-container: '#2c3e50'
  on-primary-container: '#96a9be'
  inverse-primary: '#b5c8df'
  secondary: '#526069'
  on-secondary: '#ffffff'
  secondary-container: '#d3e2ed'
  on-secondary-container: '#56656e'
  tertiary: '#122a34'
  on-tertiary: '#ffffff'
  tertiary-container: '#29404a'
  on-tertiary-container: '#93abb8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e4fb'
  primary-fixed-dim: '#b5c8df'
  on-primary-fixed: '#091d2e'
  on-primary-fixed-variant: '#36485b'
  secondary-fixed: '#d6e5ef'
  secondary-fixed-dim: '#bac9d3'
  on-secondary-fixed: '#0f1d25'
  on-secondary-fixed-variant: '#3b4951'
  tertiary-fixed: '#cde6f4'
  tertiary-fixed-dim: '#b1cad7'
  on-tertiary-fixed: '#051e28'
  on-tertiary-fixed-variant: '#334a55'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin: 40px
  section-gap: 80px
  stack-sm: 12px
  stack-md: 24px
---

## Brand & Style

The design system is built upon a foundation of precision, innovation, and clinical excellence. It reflects a future where human care and advanced technology converge seamlessly. The visual language is **Modern Corporate** with a strong leaning toward **Minimalism**, prioritizing clarity and ease of use to foster a sense of calm and reliability in high-stakes medical environments.

The target audience includes healthcare professionals who require efficiency and patients who seek a premium, trustworthy care experience. The UI evokes a "sanctuary" feel—bright, open, and meticulously organized. High-end luxury is achieved not through opulence, but through the perfect balance of generous whitespace, sophisticated typography, and subtle, intentional depth.

## Colors

This design system utilizes a palette derived from clinical environments and advanced robotics. 
- **Primary:** A deep, authoritative Slate Blue used for text and primary branding elements, providing a grounded sense of trust.
- **Secondary:** A soft, ethereal "Medical Blue" used for subtle backgrounds and hover states, evoking a sterile yet welcoming atmosphere.
- **Tertiary:** A refined Cool Grey taken from the robotic hand's metallic tones, used for secondary icons and borders.
- **Neutral:** A range of "Medical Whites" and off-whites that form the canvas of the UI, ensuring the interface feels airy and premium.

The color strategy relies on low-saturation levels to maintain a professional, high-end medical aesthetic, using high-contrast slate only where necessary for readability.

## Typography

The design system uses **Manrope** across all levels. This typeface was selected for its geometric yet organic structure, bridging the gap between clinical precision and human approachability. 

Headlines use semi-bold and bold weights with slightly tightened letter-spacing to command authority and project a premium feel. Body copy is set with generous line heights to ensure maximum readability for medical practitioners. Labels and small metadata utilize a medium weight and subtle tracking to remain legible even at small scales, ensuring the interface feels organized and data-rich without being overwhelming.

## Layout & Spacing

The layout philosophy centers on a **Fixed Grid** system to provide a sense of architectural stability. A 12-column grid is utilized for desktop views, with wide margins and gutters to give content room to breathe. 

The spacing rhythm is built on an 8px base unit. To achieve the "luxurious" feel requested, the design system leans into "oversized" padding (32px to 64px) within containers. This intentional use of negative space directs the user's focus and prevents the visual clutter often found in traditional medical software. Elements should be stacked with consistent vertical intervals to maintain a logical hierarchy.

## Elevation & Depth

Hierarchy in this design system is communicated through **Ambient Shadows** and **Tonal Layers**. Rather than using harsh borders, surfaces are separated by extremely diffused, low-opacity shadows (e.g., `box-shadow: 0 10px 30px rgba(44, 62, 80, 0.05)`). 

Backgrounds use a layered approach where the base is the neutral white, and secondary containers use a very light blue-grey tint. This creates a soft "stacking" effect that feels tactile and high-end. For interactive elements, a secondary elevation level is used to "lift" the component slightly on hover, providing subtle but clear feedback. Glassmorphism may be used sparingly for floating navigation or modals to maintain a sense of lightness and transparency.

## Shapes

The design system employs a **Rounded** shape language. A corner radius of 0.5rem (8px) is the standard for most components, striking a balance between the sharpness of medical instruments and the softness of human care. 

Large containers and cards utilize a more pronounced radius (1rem) to feel friendly and modern. Interactive elements like buttons may use a "soft" roundedness to maintain a professional look, while chips and tags can lean toward pill-shaped to distinguish them from primary action elements.

## Components

### Buttons
Primary buttons feature a solid Slate Blue background with white text and a soft, wide shadow. Secondary buttons use a ghost style with a subtle Slate Blue border or a light blue-grey background. All buttons have a minimum height of 48px to feel substantial and "premium."

### Cards
Cards are the primary organizational unit. They should have no visible border, relying instead on the "premium" ambient shadows and a pure white background against the slightly tinted neutral canvas.

### Input Fields
Fields should feel clinical and clean. They utilize a light grey-blue stroke that darkens on focus. Use ample internal padding (16px) and clear, sophisticated labels above the field.

### Chips & Status Indicators
Status indicators (e.g., "Stable," "In Progress") use soft pastel backgrounds derived from the primary and secondary colors. They are pill-shaped to differentiate them from the more structural, rectangular components of the grid.

### Lists & Data Tables
Tables should be minimalist, removing vertical lines in favor of horizontal row separation using 1px soft-grey dividers. Headers should use the `label-sm` typographic style for a professional, dashboard-like appearance.

### Specialized Components
- **Bio-Metric Pulse:** A subtle animation style for real-time data monitoring.
- **Patient Profile Header:** A high-contrast section combining the primary slate with large-scale typography for clear identity verification.