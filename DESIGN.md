---
name: Rugged Professionalism
colors:
  surface: '#f7faf4'
  surface-dim: '#d8dbd5'
  surface-bright: '#f7faf4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f5ee'
  surface-container: '#ecefe8'
  surface-container-high: '#e6e9e3'
  surface-container-highest: '#e0e3dd'
  on-surface: '#191d19'
  on-surface-variant: '#42493e'
  inverse-surface: '#2d312d'
  inverse-on-surface: '#eff2eb'
  outline: '#72796e'
  outline-variant: '#c2c9bb'
  surface-tint: '#3b6934'
  primary: '#154212'
  on-primary: '#ffffff'
  primary-container: '#2d5a27'
  on-primary-container: '#9dd090'
  inverse-primary: '#a1d494'
  secondary: '#705a46'
  on-secondary: '#ffffff'
  secondary-container: '#fbddc3'
  on-secondary-container: '#76604c'
  tertiary: '#293c44'
  on-tertiary: '#ffffff'
  tertiary-container: '#40535c'
  on-tertiary-container: '#b2c6d0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bcf0ae'
  primary-fixed-dim: '#a1d494'
  on-primary-fixed: '#002201'
  on-primary-fixed-variant: '#23501e'
  secondary-fixed: '#fbddc3'
  secondary-fixed-dim: '#ddc2a9'
  on-secondary-fixed: '#271909'
  on-secondary-fixed-variant: '#564330'
  tertiary-fixed: '#d1e6f0'
  tertiary-fixed-dim: '#b5cad4'
  on-tertiary-fixed: '#0a1e26'
  on-tertiary-fixed-variant: '#374952'
  background: '#f7faf4'
  on-background: '#191d19'
  surface-variant: '#e0e3dd'
typography:
  headline-lg:
    fontFamily: Work Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Work Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Work Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-edge: 32px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is built for the rugged, high-stakes environment of professional land clearing and forestry management. The brand personality is dependable, seasoned, and disciplined. It moves away from the "safety vest" aesthetic of general construction into a premium, specialized space that values longevity and precision.

The visual style is **Modern Corporate with Tactile influences**. It prioritizes clarity and utility, using heavy whitespace and structured grids to maintain a sense of order. Subtle textures and organic color transitions evoke the feeling of high-quality outdoor gear—functional, weather-resistant, and built to last. The UI should feel like a reliable tool in a foreman's hand: weighty but precise.

## Colors

The palette is anchored by **Deep Forest Green**, providing an immediate connection to the environment. The primary accent is a **Weathered Wood Brown**, which replaces high-visibility tones with a sophisticated, earthy warmth that signifies experience and natural integration.

- **Primary (#2D5A27):** Used for brand identity, primary actions, and success states.
- **Secondary (#7D6752):** Used for interactive accents, navigational elements, and secondary buttons.
- **Tertiary (#4A5D66):** A rugged slate used for data visualization, utility icons, and technical overlays.
- **Neutrals:** We utilize a "Stone" scale. Backgrounds use a warm off-white (#FAF9F6) to reduce glare in outdoor settings, while text uses a deep charcoal (#242824) for maximum legibility.

## Typography

The design system utilizes **Work Sans** exclusively. Its grotesque, slightly wide proportions offer exceptional readability on mobile devices and in varying light conditions. 

Headlines are set with tight tracking and heavy weights to convey strength. Body text prioritizes a generous line height (1.6) to ensure that complex technical data remains digestible. Labels utilize a slight uppercase treatment and tracking increase to differentiate meta-data from primary content, mimicking the stenciled markings found on industrial machinery.

## Layout & Spacing

This design system follows a **Fixed-Grid model** for desktop and a **Fluid-Grid model** for mobile. A strict 8px base unit governs all dimensions, ensuring a rhythmic vertical flow.

- **Grid:** 12-column system for desktop, 4-column for mobile.
- **Margins:** Generous 32px outer margins provide "breathing room" that prevents the UI from feeling cramped or chaotic.
- **Density:** Spacing is intentionally spacious (Comfortable density) to accommodate gloved interaction or high-vibration environments where precise tapping is required.

## Elevation & Depth

We utilize **Tonal Layers** rather than dramatic shadows to establish hierarchy, maintaining a clean and professional look. 

- **Level 0 (Background):** The base canvas (#FAF9F6).
- **Level 1 (Cards/Surface):** Pure white surfaces with a subtle 1px border in a muted stone tint.
- **Level 2 (Overlays):** For modals or dropdowns, use an ambient, highly diffused shadow (15% opacity, 20px blur) with a slight "Deep Forest" tint to ground the element.
- **Interactive Depth:** Buttons use a very subtle inner-shadow when pressed to simulate physical depression, enhancing the tactile feedback of the interface.

## Shapes

The shape language is **Soft (0.25rem / 4px)**. This slight rounding takes the edge off the industrial feel without becoming overly friendly or consumer-grade.

- **Buttons & Inputs:** Use the standard 4px radius.
- **Cards & Containers:** Use the `rounded-lg` (8px) token to create a distinct container hierarchy.
- **Icons:** Should feature squared ends and consistent stroke weights to match the Work Sans letterforms.

## Components

### Buttons
Primary buttons use the **Deep Forest Green** with white text. Secondary buttons use the **Weathered Wood Brown** to signify alternative paths. Ghost buttons use a 1px Slate Blue border.

### Chips & Tags
Used for equipment status (e.g., "In Use", "Maintenance"). These should be rectangular with the 4px radius, using low-saturation backgrounds (e.g., a very pale version of the Slate Blue) to keep the focus on the primary green actions.

### Input Fields
Fields feature a solid 1px Stone border. When focused, the border transitions to Deep Forest Green with a 2px thickness. Labels are always positioned above the field for maximum visibility.

### Cards
Cards are the primary organizational unit. They should have a white background, no shadow, and a 1px neutral border. Headers within cards should use the Weathered Wood Brown for the title text to create a warm, organized sectioning.

### Lists & Data Tables
Tables use a "Zebra Stripe" pattern with a very light Stone tint on alternating rows. This ensures that long rows of forestry data are easy to track across the screen.

### Specialized Components
- **Equipment Gauges:** Use the Tertiary Slate Blue for the track and Primary Green for the progress indicator.
- **Map Overlays:** Use semi-transparent layers of the Deep Forest Green for zone demarcations.