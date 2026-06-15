---
name: Executive Precision High-Contrast
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
  on-surface-variant: '#e4bebc'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#ab8987'
  outline-variant: '#5b403f'
  surface-tint: '#ffb3b1'
  primary: '#ffb3b1'
  on-primary: '#680011'
  primary-container: '#ff535b'
  on-primary-container: '#5b000e'
  inverse-primary: '#bb152c'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#929090'
  on-tertiary-container: '#2a2a2a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410007'
  on-primary-fixed-variant: '#92001c'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max-width: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

This design system is built for high-stakes professional environments where clarity and immediate impact are paramount. The personality is authoritative, decisive, and uncompromisingly modern. By leveraging a high-contrast dark theme, we create a focused workspace that minimizes ocular strain in low-light environments while emphasizing critical data points through aggressive accentuation.

The design style is a hybrid of **Minimalism** and **High-Contrast Modern**. It relies on deep blacks to create infinite depth, allowing white typography and vibrant red accents to "pop" with surgical precision. Every element exists to serve a function, stripping away unnecessary decoration in favor of structural integrity and visual hierarchy.

## Colors

The palette is strictly controlled to maintain executive gravity. 

- **Primary Background**: Pure Black (#000000) is used for the base level of the application to ensure maximum contrast and power efficiency on OLED displays.
- **Surface Tiers**: Progressive shades of deep grey define the Z-axis. Surface-1 is for primary containers, while Surface-3 is reserved for elevated modals or hovered states.
- **The Red Accent**: #E63946 is the "Action Color." It is used sparingly but boldly for primary Calls to Action (CTAs), critical alerts, and active navigational states. 
- **Typography**: Primary text is pure White (#FFFFFF) for maximum legibility. Secondary text uses a 60% opacity white to create a clear information hierarchy without introducing new hues.

## Typography

The design system utilizes **Manrope** exclusively to maintain a clean, technical, and modern aesthetic. 

- **Weight Usage**: Bold (700) and ExtraBold (800) weights are reserved for headlines to anchor the page. Regular (400) is used for long-form body text to ensure breathability.
- **Scale**: The typographic scale is aggressive. Large display headers provide a clear entry point, while labels use slight letter-spacing and uppercase styling to differentiate UI metadata from content.
- **Contrast**: On the black background, text weights may appear slightly heavier. Subtle tracking (letter-spacing) is added to display sizes to maintain a sophisticated, "engineered" look.

## Layout & Spacing

This design system follows a **Fixed Grid** philosophy for desktop to maintain a "dashboard" feel, switching to a fluid model for mobile devices.

- **Grid**: A 12-column grid is used for desktop (1280px max-width). Components should align to the grid lines to emphasize the "Precision" aspect of the brand.
- **Rhythm**: All spacing is derived from an 8px base unit. 24px (3 units) is the standard padding for cards and containers, creating a spacious but dense information environment.
- **Mobile Adaption**: On mobile, margins shrink to 16px. Vertical stacks are preferred over horizontal scrolling to keep the executive experience fast and efficient.

## Elevation & Depth

In a pure black environment, traditional shadows are ineffective. Elevation is conveyed through **Tonal Layering** and **Stroke Definition**:

1.  **Level 0 (Base)**: Pure #000000. Used for the main canvas.
2.  **Level 1 (Card/Container)**: #121212. These surfaces sit "above" the base. They are defined by a subtle 1px border (#333333) rather than a shadow.
3.  **Level 2 (Popovers/Modals)**: #1E1E1E. These elements use a sharp 1px white border at 20% opacity to "cut" through the darkness.
4.  **Interaction**: Hover states on containers should increase the border brightness or slightly lighten the surface hex, never using glows or blurs unless they are specific to the Red Accent color.

## Shapes

The shape language is **Soft (0.25rem)**. 

While the system is professional and rigid, a micro-radius on corners prevents the UI from feeling dated or hostile. 
- **Buttons and Inputs**: Use the base 0.25rem (4px) radius. 
- **Large Cards**: May scale to 0.5rem (8px) to soften the overall layout.
- **Red Accents**: Must strictly follow these radius rules—no pill shapes or circular buttons are permitted, as they break the structured, executive grid.

## Components

### Buttons
- **Primary**: Solid Red (#E63946) background with White (#FFFFFF) text. Bold weight. No border.
- **Secondary**: Transparent background with a 2px White border. White text.
- **Ghost**: Transparent background, White text at 60% opacity.

### Input Fields
- **Default**: Surface-2 background (#1E1E1E) with a subtle bottom-border only (#333333). 
- **Focus**: The bottom-border transitions to Red (#E63946) with a 1px thickness.

### Cards
- Background: Surface-1 (#121212).
- Border: 1px Solid #333333.
- Layout: Use 24px internal padding for all content.

### Status Chips
- High-contrast indicators. For "Active" or "Critical," use a solid Red background. For neutral states, use Surface-3 with white text.

### Data Lists
- Alternating row colors are not used. Instead, rows are separated by 1px borders (#1A1A1A). On hover, the entire row shifts to Surface-2 (#1E1E1E).