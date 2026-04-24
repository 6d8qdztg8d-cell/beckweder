---
name: Artisanal Heritage
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
  on-surface-variant: '#444748'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#7e562e'
  on-secondary: '#ffffff'
  secondary-container: '#fdc796'
  on-secondary-container: '#79512a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#261900'
  on-tertiary-container: '#a17f3b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#ffdcbf'
  secondary-fixed-dim: '#f1bc8c'
  on-secondary-fixed: '#2d1600'
  on-secondary-fixed-variant: '#633f19'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#e9c176'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4201'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-xl:
    fontFamily: Noto Serif
    fontSize: 4.5rem
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h1:
    fontFamily: Noto Serif
    fontSize: 3rem
    fontWeight: '400'
    lineHeight: '1.2'
  h2:
    fontFamily: Noto Serif
    fontSize: 2.25rem
    fontWeight: '400'
    lineHeight: '1.3'
  h3:
    fontFamily: Noto Serif
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Manrope
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
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

The visual identity of this design system centers on the intersection of Swiss precision and the warm, tactile nature of artisanal baking. It evokes the feeling of a high-end boutique—quietly confident, meticulously crafted, and deeply rooted in tradition without appearing dated.

The design style follows a **Minimalist** philosophy enhanced by **Tactile** elements. By prioritizing generous whitespace and high-fidelity photography of grain textures and flour-dusted crusts, the UI steps back to let the product quality speak. The emotional response is one of "Quiet Luxury": the user should feel they are entering an establishment where time slows down and quality is never compromised.

## Colors

The palette is anchored in **Creamy White** and **Beige**, providing a soft, organic canvas that avoids the clinical feel of pure white. **Deep Charcoal** is utilized for primary typography and structural elements to ensure readability and a modern Swiss edge. 

**Warm Brown** serves as a bridge to the bakery's heritage, used for interactive elements and subtle separators. **Gold Accents** are applied sparingly—reserved for highlights, hover states, or "Premium" signifiers—to maintain a sophisticated rather than flashy aesthetic. Contrast ratios are strictly maintained to ensure that the elegance does not sacrifice accessibility.

## Typography

This design system employs a classic "Serif for Headlines, Sans-Serif for Body" pairing. **Noto Serif** provides the "Tradition" component, used for editorial headlines and storytelling moments where character and prestige are paramount. It should be typeset with slightly tighter tracking in large formats to feel like a premium broadsheet or luxury magazine.

**Manrope** provides the "Modern" counterpoint. Its clean, geometric construction ensures that functional information—prices, ingredients, and navigation—remains legible and grounded. The `label-caps` style is used for small metadata and navigational headers to inject a sense of Swiss organizational rigor.

## Layout & Spacing

The layout utilizes a **Fixed Grid** model to maintain editorial control over the visual rhythm. A 12-column grid system is used for desktop, with generous margins (80px+) to prevent content from feeling crowded. 

Whitespace is treated as a premium design element rather than "empty" space. Large vertical gaps (using the `xl` spacing unit) separate distinct sections, such as "Our Process" and "Daily Offerings," to allow the user's eye to rest. Elements should rarely touch; the use of padding within cards and containers should feel expansive, mirroring the airy interior of a high-end bakery.

## Elevation & Depth

To reflect a premium atmosphere, this design system avoids heavy, dark shadows. Depth is achieved through **Tonal Layers** and **Ambient Shadows**. 

Surfaces that require elevation (such as cards or dropdowns) use a very soft, diffused shadow with a hint of the `secondary_color_hex` (Warm Brown) in the tint to keep it feeling organic. The backdrop for floating elements should use a subtle blur effect to maintain focus while suggesting a layered, sophisticated physical environment. Fine, 1px lines in light beige or gold are used to delineate sections without adding visual weight.

## Shapes

The shape language is defined by **Rounded** corners that soften the precision of the Swiss-inspired layout. A 0.5rem (8px) base radius is applied to standard buttons and inputs, while `rounded-xl` (1.5rem) is reserved for product cards and featured imagery containers. 

This specific level of roundedness evokes the softness of dough and the curves of baked goods, contrasting against the sharp, disciplined lines of the grid. All image containers must maintain these radii to ensure consistency across the visual narrative.

## Components

### Buttons
Primary buttons use the **Deep Charcoal** background with **Creamy White** text, emphasizing authority. Secondary buttons utilize a "Fine Line" outline style with the **Warm Brown** color. Hover states should be smooth transitions, either subtly shifting the background color or introducing a gentle lift through ambient shadows.

### Cards
Cards are the primary vehicle for product displays. They feature a white surface, a `rounded-xl` corner radius, and a subtle 1px border in a pale beige. Images within cards should always be top-aligned and full-bleed to the top and side edges of the card.

### Input Fields
Inputs follow a minimalist "Modern" approach: a simple bottom border or a very light-filled background with no side borders. Labels use the `label-caps` typography style to remain unobtrusive but clear.

### Specialized Components
- **Texture Overlays:** Subtle grain or parchment textures may be used as background fills for specific call-to-action sections to reinforce the artisanal theme.
- **The Crest:** The traditional family crest should be used as a watermark or a decorative element in the footer and on "About Us" sections, rendered in a monochrome Gold or Brown.
- **Smooth Transitions:** Page transitions and hover effects must be timed at 300ms–500ms with an `ease-in-out` curve to mimic the slow, deliberate nature of hand-craftsmanship.