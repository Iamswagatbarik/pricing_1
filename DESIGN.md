---
name: Obsidian Agency
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c7c8'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c6c6c7'
  primary: '#ffffff'
  on-primary: '#2f3131'
  primary-container: '#e2e2e2'
  on-primary-container: '#636565'
  inverse-primary: '#5d5f5f'
  secondary: '#c7c6c6'
  on-secondary: '#2f3131'
  secondary-container: '#484949'
  on-secondary-container: '#b8b8b8'
  tertiary: '#ffffff'
  on-tertiary: '#303030'
  tertiary-container: '#e4e2e1'
  on-tertiary-container: '#656464'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  headline-lg:
    fontFamily: Source Serif 4
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Source Serif 4
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Source Serif 4
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
  headline-lg-mobile:
    fontFamily: Source Serif 4
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

This design system embodies an authoritative, premium aesthetic tailored for a high-end digital services agency. It leverages a **Minimalist** philosophy with a focus on editorial-grade typography and structured layouts. The emotional goal is to evoke confidence, precision, and exclusivity. 

By utilizing deep monochromatic tones and generous whitespace, the UI recedes to let the content and data take center stage. The style is "New Corporate"—it is professional and grounded but maintains a sharp, contemporary edge through the use of fine-line borders and high-contrast text.

## Colors

The palette is strictly monochromatic to maintain a high-end, executive feel. 

- **Primary:** Pure white is used for primary headings and critical interface actions, ensuring maximum legibility against the dark background.
- **Secondary:** A medium-grey used for secondary information, icons, and deactivated states.
- **Tertiary:** A deep charcoal used for subtle UI elements like hover states or container backgrounds.
- **Neutral/Background:** The core background is a deep, near-black charcoal (#1A1A1A), which reduces eye strain while maintaining a premium "ink" look compared to pure #000000.

Borders should utilize a low-opacity white (approx. 10-15%) to create "hairline" separators that appear crisp but not distracting.

## Typography

This system uses a sophisticated pairing of a serif for authority and a clean sans-serif for functional clarity.

- **Headlines:** Source Serif 4 provides a literary, established feel. Use tight letter-spacing for large display sizes to maintain a modern editorial look.
- **Body & UI:** Hanken Grotesk offers a sharp, geometric clarity that balances the traditional nature of the serif.
- **Labels:** Small caps with increased tracking (letter-spacing) are used for table headers and overlines to create a sense of structure and hierarchy.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to preserve the intentional whitespace characteristic of luxury branding. 

- **Desktop:** 12-column grid with a 1200px max-width.
- **Tablet:** 8-column grid with fluid margins.
- **Mobile:** 4-column grid with 16px side margins.

Spacing follows a 4px base unit. For high-end "breathability," prioritize the `xl` (40px) and `lg` (24px) tokens for vertical section spacing. Data-heavy views like pricing tables should use horizontal lines rather than vertical columns to maintain a clean, readable flow.

## Elevation & Depth

To maintain the flat, professional aesthetic of the reference, this design system avoids heavy drop shadows.

- **Low-contrast outlines:** Depth is primarily established through 1px borders using a 10% white stroke.
- **Tonal Layering:** Interactive elements like cards or buttons may use a slightly lighter background (#2C2C2C) to indicate elevation above the base surface.
- **Backdrop Blurs:** For overlays or navigation bars, use a heavy backdrop blur (20px) with a semi-transparent dark tint to create a "glass" effect that feels expensive and modern.

## Shapes

The shape language is **Sharp (0)**. 

To reinforce the digital agency’s precision and professional rigor, all containers, buttons, and input fields use 0px border radii. This architectural approach distinguishes the brand from more "consumer-friendly" rounded apps, signaling a focus on enterprise-grade results and sophisticated design.

## Components

- **Buttons:** Primary buttons are solid white with black text, strictly rectangular. Secondary buttons use a white 1px border with no fill.
- **Pricing Tables:** Use subtle horizontal rules (1px, 10% white) to separate rows. Feature names should be left-aligned, while data points are centered or right-aligned.
- **Input Fields:** Bottom-border only (1px white) or full rectangular outline. No rounded corners. Focus state increases the border opacity to 100%.
- **Chips/Badges:** Small, rectangular tags with thin borders. Use label-caps typography.
- **Cards:** Defined by a 1px border rather than a shadow. On hover, the background can shift slightly lighter to #2C2C2C.
- **Icons:** Use thin-stroke (1px or 1.5px) monochrome icons. Avoid filled icons unless used as a status indicator (like a checkmark).