---
name: Atelier Architectural
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#4b4640'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#7d766f'
  outline-variant: '#cec5bd'
  surface-tint: '#615e5b'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1d1b19'
  on-primary-container: '#878380'
  inverse-primary: '#cbc5c2'
  secondary: '#745a32'
  on-secondary: '#ffffff'
  secondary-container: '#ffdaa8'
  on-secondary-container: '#795e36'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1c16'
  on-tertiary-container: '#86847b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e7e1de'
  primary-fixed-dim: '#cbc5c2'
  on-primary-fixed: '#1d1b19'
  on-primary-fixed-variant: '#494644'
  secondary-fixed: '#ffddb0'
  secondary-fixed-dim: '#e4c191'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#5a421d'
  tertiary-fixed: '#e6e2d8'
  tertiary-fixed-dim: '#cac6bd'
  on-tertiary-fixed: '#1c1c16'
  on-tertiary-fixed-variant: '#484740'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 4.5rem
    fontWeight: '400'
    lineHeight: 5rem
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Playfair Display
    fontSize: 2.75rem
    fontWeight: '400'
    lineHeight: 3.25rem
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 3.25rem
    fontWeight: '400'
    lineHeight: 3.75rem
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 2.25rem
    fontWeight: '400'
    lineHeight: 2.75rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 2.25rem
    fontWeight: '400'
    lineHeight: 2.75rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 1.75rem
    fontWeight: '500'
    lineHeight: 2.25rem
    letterSpacing: 0em
  title:
    fontFamily: Playfair Display
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.875rem
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.65rem
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.45rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.12em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.6875rem
    fontWeight: '600'
    lineHeight: 0.875rem
    letterSpacing: 0.16em
spacing:
  gutter: 2rem
  gutter-sm: 1rem
  margin: 4rem
  margin-sm: 1.5rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.5rem
  space-lg: 2.5rem
  space-xl: 4rem
---

## Brand & Style

This design system channels an architectural editorial language tailored for luxury interior architecture, high-end residential estates, and bespoke commercial spaces. It merges refined minimalism with classical structural discipline, capturing the tactile serenity of raw travertine, warm French limestone, and patinated bronze.

The aesthetic evokes quiet authority, enduring material luxury, and meticulous attention to scale and proportion. Interfaces must feel like printed architectural monographs: expansive negative space, disciplined column structures, razor-thin framing rules, and deliberate typographical pacing. Interactions are subtle and deliberate, eschewing abrupt transitions in favor of soft, natural motion.

## Colors

The palette is derived directly from mineral textures, architectural materials, and natural patinas:

- **Primary (`#1C1A18`)**: Deep Espresso Charcoal. Serves as the foundational color for high-contrast typography, crisp linear frames, and dominant primary interactive states.
- **Secondary (`#B8986B`)**: Warm Muted Bronze / Champagne. Applied strictly as an accent for focal highlights, curated metadata, active states, and editorial flourishes. Avoid using over large surface fills.
- **Tertiary (`#E8E4DA`)**: Soft Calacatta & Travertine Stone. Used for secondary card backgrounds, subtle layer separations, and hovering states.
- **Neutral (`#F6F4EF`)**: Warm Alabaster Canvas. The principal surface background establishing an organic, warm gallery light across the interface.

Supplementary functional tones:
- **Surface Variant / Border Line (`#E2DDD2`)**: Ultra-delicate hairline divider tone.
- **Muted Text / Caption (`#6B665F`)**: Low-strain secondary copy supporting hierarchy without competing with primary headings.

## Typography

The typography pairs the poise of a high-fashion architectural serif (**Playfair Display**) with the crisp, modern legibility of a geometric sans (**Plus Jakarta Sans**).

- **Playfair Display**: Dictates editorial presence. Headlines favor generous line height and delicate optical weights (`400` and `500`), creating an open, unhurried cadence across editorial compositions.
- **Plus Jakarta Sans**: Provides clarity and functional balance for body text, technical dimension specifications, material notes, and navigation elements.
- **Labels & Micro-Copy**: Rendered exclusively in uppercase with extended tracking (`0.12em` to `0.16em`) to reflect architectural blueprint and gallery indexing traditions.

## Layout & Spacing

The layout is grounded in a disciplined 12-column architectural grid defined by proportional modular rhythm and generous breathing room. 

- **Desktop (>= 1200px)**: 12-column grid, `margin: 4rem` (or max-width containment at `1440px` with centered auto-margins), `gutter: 2rem`. Editorial modules often feature asymmetrical offsets (e.g., imagery spanning 7 columns paired with empty 1-column offsets and 4 columns of editorial narrative).
- **Tablet (768px - 1199px)**: 8-column grid, `margin: 2.5rem`, `gutter: 1.5rem`.
- **Mobile (< 768px)**: 4-column grid, `margin-sm: 1.5rem`, `gutter-sm: 1rem`.

Vertical pacing operates on multiples of `1.5rem` and `4rem`, deliberately leaving wide passages of negative space around imagery and typography to preserve an atmosphere of curated luxury.

## Elevation & Depth

To reflect modern luxury and tactile architectural materials, this system rejects heavy drop shadows in favor of **tonal layers** and **delicate hairline borders**.

- **Surface Tiers**: Base canvas begins at `#F6F4EF` (Alabaster Stone). Elevated surfaces shift subtly to `#E8E4DA` or pure semi-matte white (`#FFFFFF`) to establish soft, planar distinction.
- **Hairline Framing**: Structural depth relies on 1px borders colored in `#E2DDD2`. Elements sit flush against each other separated only by precise, architectural grid lines.
- **Atmospheric Ambient Shadow**: For floating modals, persistent navigation headers, and lightbox overlays, depth is produced via an ultra-soft, diffused shadow:
  `box-shadow: 0 16px 40px -12px rgba(28, 26, 24, 0.06), 0 2px 6px 0 rgba(28, 26, 24, 0.02)`.

## Shapes

The shape system employs pure architectural geometry (`0` - Sharp). All containers, interactive components, imagery wrappers, and dividers are defined by exact 90-degree corners.

Sharp angles echo structural stonework, marble slabs, joinery, and floor plans. Buttons, cards, and modal panels feature crisp perimeters framed by 1px hairline rules, creating an aesthetic that feels crafted, permanent, and tailored.

## Components

### Buttons
- **Primary Button**: Solid Deep Charcoal (`#1C1A18`) fill, Neutral (`#F6F4EF`) uppercase label typography, 0px border-radius, vertical padding `space-sm`, horizontal padding `space-lg`. Hover: Smooth transition to Secondary Bronze (`#B8986B`).
- **Secondary / Outline Button**: Transparent background, 1px solid border (`#1C1A18`), charcoal uppercase text. Hover: Fill shifts to `#1C1A18`, text transitions to `#F6F4EF`.
- **Text / Editorial Action**: Label styled with `label-md`, accompanied by a minimal horizontal trailing rule (`16px` width) that expands on hover with a `0.3s cubic-bezier(0.2, 0.8, 0.2, 1)` easing.

### Cards (Project & Material Showcases)
- Zero-radius layout.
- Imagery rendered in 4:5 or 16:9 ratios with flush architectural framing (`1px solid #E2DDD2`).
- Content metadata sits beneath the image separated by a hairline rule: Project Title in `Playfair Display` (`headline-sm`), Location & Year set in `label-sm` tracked uppercase in bronze (`#B8986B`).
- Hover states employ slow, subtle image scaling (`scale(1.025)`) within a hard-clipped container.

### Chips & Material Tags
- Architectural pill-free design: strictly rectangular tags.
- Background in Stone (`#E8E4DA`) or transparent with a 1px `#E2DDD2` border.
- Text in `label-sm` with charcoal or bronze coloring.
- Padding: `0.375rem 0.75rem`.

### Form Fields & Inputs
- Understated architectural inputs: Minimal baseline-only underline (1px `#1C1A18`) or full 1px border (`#E2DDD2`) with no rounded corners.
- Background: Pure White (`#FFFFFF`) or transparent over Alabaster.
- Placeholder text in `#6B665F`. Focused state transforms border to `#B8986B` (Warm Bronze).

### Checkboxes & Radios
- Checkboxes: Exact squares (16px x 16px), 1px solid `#1C1A18`, sharp corners. Checked state features a solid Charcoal fill with a minimal white checkmark or inner stone square.
- Radio Buttons: Circular framing (16px x 16px), 1px solid `#1C1A18`, filled with an inner floating solid circle (8px) upon selection.

### Architectural Accordions & Specification Lists
- Divided by horizontal 1px hairline dividers (`#E2DDD2`).
- Expanding panels for project dimensions, material finishes, and spatial blueprints.
- Indicators use delicate `+` and `−` symbols in Playfair Display rather than generic chevron icons.