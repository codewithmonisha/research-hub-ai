---
name: ResearchHub AI
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#464555'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#712ae2'
  on-secondary: '#ffffff'
  secondary-container: '#8a4cfc'
  on-secondary-container: '#fffbff'
  tertiary: '#7e3000'
  on-tertiary: '#ffffff'
  tertiary-container: '#a44100'
  on-tertiary-container: '#ffd2be'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb695'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7b2f00'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.03em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-md:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.02em
  mono:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  giant: 80px
---

## Brand & Style
The design system embodies a premium, high-utility aesthetic that balances the technical rigor of a developer tool with the sophisticated clarity of a leading AI platform. Drawing inspiration from OpenAI’s expansive whitespace and Linear’s obsessive attention to modular detail, the system evokes a sense of "intellectual calm."

The visual style is **Modern/Minimalist** with **Glassmorphic** accents. It prioritizes information density without clutter, using thin borders and tonal layering to create a structured, "workbench" environment. The emotional response should be one of precision, reliability, and cutting-edge intelligence.

## Colors
The palette is rooted in a sophisticated range of "cool" neutrals. Surfaces use off-whites and very subtle grays to distinguish functional areas without relying on heavy shadows. 

- **Primary & Secondary**: Indigo and Purple are reserved for high-intent actions, active states, and AI-driven insights.
- **Borders**: High-contrast, 1px borders in `#E5E7EB` are the primary method of containment, replacing traditional drop shadows to maintain a flat, modular appearance.
- **Accents**: Micro-gradients bridging Indigo and Purple are used exclusively for primary call-to-actions to provide a "premium" depth.

## Typography
The system uses **Hanken Grotesk** for headings to provide a sharp, contemporary edge with tight tracking. **Inter** handles body copy for maximum legibility in research-heavy contexts. **Geist** is utilized for labels, metadata, and technical inputs to reinforce the "tooling" nature of the product.

Hierarchy is established through significant scale shifts and weight contrast. Headings should always feel tight and impactful, while body copy remains airy and readable.

## Layout & Spacing
The design system employs a strict **4px/8px grid**. Whitespace is used aggressively to separate logical sections rather than lines where possible, though 1px borders remain the final arbiter of container boundaries.

The layout is a **fixed-fluid hybrid**: the main container caps at 1280px for readability, centered on the screen. Sidebars and navigation panels use fixed widths (e.g., 240px or 280px) to maintain consistent "workbench" proportions across screen sizes.

## Elevation & Depth
Depth is created through "modular stacking" rather than traditional elevation:
- **Level 0 (Base)**: `#F9FAFB` background.
- **Level 1 (Card/Container)**: White surface with a 1px `#E5E7EB` border.
- **Level 2 (Popovers/Modals)**: White surface, 1px border, and a "Linear-style" shadow: a very large, ultra-soft blur (32px+) with low opacity (4-8%) to suggest float without weight.
- **Navigation**: Sidebars and headers use **Glassmorphism**—a semi-transparent background (`rgba(255, 255, 255, 0.7)`) with a 12px backdrop-blur filter to maintain context of the content beneath.

## Shapes
A consistent **8px (0.5rem)** radius is applied to all interactive elements, including buttons, input fields, and card containers. This "Soft" approach balances the sharpness of the typography and thin borders, ensuring the sophisticated tech aesthetic doesn't feel overly aggressive or cold.

## Components
- **Buttons**: Primary buttons use a subtle top-to-bottom gradient (Indigo to Purple) with a 1px inner light border for a "pressed" tactile feel. Secondary buttons are "ghost" style with a 1px neutral border.
- **Cards**: Use a white background, 1px `#E5E7EB` border, and no shadow. On hover, the border darkens to `#D1D5DB`.
- **Inputs**: Minimalist style. No background fill, just a 1px bottom border or full border depending on context. Focus states use a subtle 2px indigo outer ring with 0px offset.
- **Chips**: Small, 12px Geist-font labels with a `#F3F4F6` background and no border. 
- **AI Modules**: Any component performing AI reasoning should feature a subtle "glow" or a specialized micro-gradient border to distinguish it from static data components.
- **Lists**: Clean rows separated by 1px horizontal rules, using `body-md` for primary text and `label-md` for metadata.