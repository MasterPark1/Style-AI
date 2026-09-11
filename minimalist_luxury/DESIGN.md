---
name: Minimalist Luxury
colors:
  surface: '#fbf9f9'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dcdddd'
  on-secondary-container: '#5f6161'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca730'
  on-tertiary-container: '#4f3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fbf9f9'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  button:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style
The design system is anchored in the "Minimalist Luxury" aesthetic, targeting an affluent, style-conscious audience. The brand personality is authoritative yet understated, reflecting the confidence of high-end editorial fashion. 

The UI prioritizes extreme clarity and purposeful negative space to create an "art gallery" effect where content is treated as a curated exhibit. It avoids decorative clutter, relying instead on impeccable typography, a restricted color palette, and subtle tactile cues. The goal is to evoke an emotional response of calm sophistication and exclusive professional guidance.

## Colors
This design system utilizes a high-contrast, limited palette to maintain a premium feel. 

- **Deep Charcoal (#1A1A1A):** Used for primary typography, borders, and structural elements. It provides a grounded, authoritative foundation.
- **Soft Bone White (#F5F5F5):** The primary background color. It is softer than pure white, reducing eye strain and adding a subtle warmth reminiscent of high-quality stationery.
- **Fashion Gold (#D4AF37):** Used sparingly as an accent for call-to-actions, active states, and premium indicators. It should never dominate the screen.
- **Muted Greyscale:** A series of neutrals derived from Charcoal are used for secondary text and subtle dividers to maintain hierarchy without breaking the minimalist aesthetic.

## Typography
The typographic scale is designed for editorial impact. 

**Playfair Display** serves as the primary voice for headlines. Its high-contrast strokes and elegant serifs communicate fashion authority. Headlines should use generous top-margin spacing to breathe.

**Inter** provides a functional, modern counterpoint for all body copy and UI elements. Its neutrality ensures legibility and reinforces the "professional service" aspect of the brand. Use the "Label Caps" style for overlines and small metadata to add a structured, catalog-like feel to the interface.

## Layout & Spacing
The layout follows a strict 12-column fixed grid on desktop, centering content to maintain a focused, boutique feel. 

- **Generous Margins:** Large horizontal margins (64px+) on desktop push content inward, suggesting exclusivity.
- **Section Breathing Room:** Use significant vertical gaps (up to 120px) between major content sections to prevent the UI from feeling "crowded" or "salesy."
- **Mobile Reflow:** On mobile, the grid collapses to 4 columns. Typography scales down specifically for the Display-LG role to ensure headlines do not break awkwardly. 
- **Alignment:** Consistent left-alignment is preferred for long-form content, while center-alignment is reserved for high-impact hero moments.

## Elevation & Depth
Depth in this design system is achieved through **Tonal Layering** rather than heavy shadows. 

- **Flat Surfaces:** Surfaces are primarily flat, using 1px hair-line borders in a light grey (#E0E0E0) to define boundaries between sections.
- **Subtle Ambient Shadows:** When an element must float (like a modal or a dropdown), use an extremely diffused, low-opacity shadow (e.g., `box-shadow: 0 20px 40px rgba(0,0,0,0.04)`). 
- **Active State Elevation:** Interactive elements should not "pop" off the screen. Instead, use a slight color shift or a thin, sharp Fashion Gold border to indicate focus or selection.

## Shapes
To maintain a high-end, architectural aesthetic, the design system utilizes **Sharp (0px)** corners. 

The absence of roundedness communicates precision, discipline, and a modern "couture" sensibility. This applies to buttons, input fields, image containers, and cards. Circles are permitted only for specific functional icons or user avatars to provide a singular point of organic contrast.

## Components
- **Buttons:** Primary buttons are solid Deep Charcoal with white text, sharp corners, and a "Button" typography style. Secondary buttons use a 1px Charcoal border with no fill. The Fashion Gold is reserved for "Book Now" or "VIP" specific actions.
- **Input Fields:** Minimalist design featuring only a bottom border (1px) in light grey. The border thickens and turns Charcoal upon focus. Labels use the "Label Caps" style.
- **Cards:** No shadows or background fills. Cards are defined by generous padding and thin, 1px grey borders. Images within cards must take up 100% of the top width.
- **Chips/Tags:** Small, rectangular boxes with 1px borders. No background fill. Text is Inter-Bold at 10px, all-caps.
- **Checkboxes/Radios:** Custom-styled as sharp squares or circles with a thin Charcoal stroke. Selected states use a solid Charcoal fill or a small Gold dot.
- **Navigation:** A clean, fixed top bar with high transparency (backing blur optional) and "Label Caps" links. Include a distinctive "Profile" or "Closet" link to emphasize the personal service aspect.