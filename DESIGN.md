---
name: Dolce Vita Modern
colors:
  surface: '#fff8f7'
  surface-dim: '#f0d4d0'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ee'
  surface-container: '#ffe9e6'
  surface-container-high: '#ffe2de'
  surface-container-highest: '#f9dcd9'
  on-surface: '#271816'
  on-surface-variant: '#4d4446'
  inverse-surface: '#3d2c2a'
  inverse-on-surface: '#ffedea'
  outline: '#7f7476'
  outline-variant: '#d0c3c5'
  surface-tint: '#6a5b5e'
  primary: '#6a5b5e'
  on-primary: '#ffffff'
  primary-container: '#f9e4e8'
  on-primary-container: '#746568'
  inverse-primary: '#d5c2c6'
  secondary: '#625e58'
  on-secondary: '#ffffff'
  secondary-container: '#e5dfd7'
  on-secondary-container: '#66625c'
  tertiary: '#635e53'
  on-tertiary: '#ffffff'
  tertiary-container: '#f1e8da'
  on-tertiary-container: '#6e685d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f2dde1'
  primary-fixed-dim: '#d5c2c6'
  on-primary-fixed: '#24191c'
  on-primary-fixed-variant: '#514347'
  secondary-fixed: '#e8e1da'
  secondary-fixed-dim: '#ccc6be'
  on-secondary-fixed: '#1e1b17'
  on-secondary-fixed-variant: '#4a4641'
  tertiary-fixed: '#eae1d4'
  tertiary-fixed-dim: '#cec5b8'
  on-tertiary-fixed: '#1f1b13'
  on-tertiary-fixed-variant: '#4b463c'
  background: '#fff8f7'
  on-background: '#271816'
  surface-variant: '#f9dcd9'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  script-accent:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '400'
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
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The design system is rooted in the "Dolce Vita" philosophy—capturing the effortless elegance and sensory indulgence of a high-end Italian pasticceria. It targets a discerning audience that values quality, provenance, and aesthetic presentation.

The visual style blends **Modern Luxury** with **Glassmorphism**. It utilizes soft, translucent layers and organic depth to create a UI that feels light and airy, much like a perfectly whipped gelato. The interface serves as a sophisticated frame for high-end food photography, which should always be high-key, vibrant, and texturally rich. The emotional response is one of calm indulgence, reliability, and "shareable" beauty.

## Colors

The palette is a tonal journey through dessert ingredients. The **Primary Baby Pink** acts as the brand's romantic signature, used for highlights and soft backgrounds. The **Secondary Cream** and **Warm Beige Background** provide a sophisticated, non-sterile foundation that feels more artisanal than pure white.

**Dark Chocolate Brown** replaces traditional black for all typography and iconography to maintain warmth and high contrast without the harshness of a digital neutral. For interactive states, use a slightly desaturated version of the Primary Pink to indicate hover or active transitions.

## Typography

Typography centers on the contrast between the authoritative, high-contrast strokes of **Playfair Display** and the clean, geometric precision of **Montserrat**. 

- **Display & Headlines:** Use Playfair Display to evoke a literary, premium feel. For "Our Story" or specialized accents, use the italicized serif to mimic a modern calligraphic touch.
- **Body & Interface:** Montserrat provides a functional counterbalance. Use `label-md` with slight tracking for navigation and secondary actions to ensure they feel organized and modern.
- **Hierarchy:** Maintain generous line-heights to support the "airy" brand personality.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop to maintain the "editorial" feel of a luxury magazine, transitioning to a fluid model for mobile.

- **Grid:** A 12-column system with wide 24px gutters.
- **Whitespace:** Use "generous breathing room." Section vertical gaps should be significant (minimum 120px) to separate different "experiences" or flavor profiles.
- **Mobile Reflow:** On mobile, margins shrink to 20px, and multi-column cards reflow into a single-stack vertical scroll or a horizontal "peek" carousel for product flavors.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and **Ambient Shadows** rather than solid borders.

- **Surfaces:** Use semi-transparent Cream (#FFF8F0) with a 20px-32px backdrop blur for navigation bars and overlay modals.
- **Shadows:** Shadows are extremely diffused (Blur: 40px, Spread: -10px) using a tinted Dark Chocolate Brown at 5-8% opacity. This prevents the "dirty" look of grey shadows on warm backgrounds.
- **Depth:** Content cards should feel like they are floating slightly above the warm beige base, creating a sense of lightness.

## Shapes

The shape language is organic and soft, avoiding all sharp corners to mimic the fluidity of gelato and desserts.

- **Standard Radius:** 0.5rem (8px) for small interactive elements like inputs and buttons.
- **Large Radius:** 1.5rem (24px) for product cards and main layout containers.
- **Image Treatment:** Photography should either be contained within `rounded-xl` containers or use organic "watercolor" mask shapes to blend into the background as seen in the brand narrative sections.

## Components

### Buttons
- **Primary:** Dark Chocolate Brown background with Cream text. Rounded corners (8px). Subtle lift shadow on hover.
- **Secondary:** Transparent background with a 1px Dark Chocolate Brown border. 
- **Tertiary/Ghost:** Primary Pink text, no border, used for low-priority navigation.

### Cards
Cards are the primary vehicle for flavor showcases. Use the `rounded-xl` (24px) radius. The card body should be the Secondary Cream color. Images within cards should have no bottom radius where they meet the text area to maintain a unified structure.

### Input Fields & Selects
Inputs use the Secondary Cream background with a very soft Warm Beige border. Labels always sit above the field in `label-md` Montserrat.

### Chips & Tags
Used for dietary labels (e.g., "Vegan", "Gluten-Free"). These should be pill-shaped with a Primary Pink background and Dark Chocolate Brown text, using the `label-md` typography style at a smaller scale.

### Navigation
The header uses a glassmorphic background. Navigation links use Montserrat with a 2px underline transition in Primary Pink on hover.