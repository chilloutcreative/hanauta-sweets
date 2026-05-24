---
name: Artisanal Organic Minimal
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
  on-surface-variant: '#504441'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#827470'
  outline-variant: '#d4c3be'
  surface-tint: '#77574d'
  primary: '#442a22'
  on-primary: '#ffffff'
  primary-container: '#5d4037'
  on-primary-container: '#d4ada1'
  inverse-primary: '#e7bdb1'
  secondary: '#4e635a'
  on-secondary: '#ffffff'
  secondary-container: '#cee5da'
  on-secondary-container: '#52675e'
  tertiary: '#1c3433'
  on-tertiary: '#ffffff'
  tertiary-container: '#334b49'
  on-tertiary-container: '#a0bab7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#e7bdb1'
  on-primary-fixed: '#2c160e'
  on-primary-fixed-variant: '#5d4037'
  secondary-fixed: '#d1e8dd'
  secondary-fixed-dim: '#b5ccc1'
  on-secondary-fixed: '#0b1f18'
  on-secondary-fixed-variant: '#374b43'
  tertiary-fixed: '#cde8e5'
  tertiary-fixed-dim: '#b1ccc9'
  on-tertiary-fixed: '#061f1e'
  on-tertiary-fixed-variant: '#334b49'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max-desktop: 1200px
  gutter-desktop: 24px
  margin-desktop: 48px
  gutter-mobile: 16px
  margin-mobile: 20px
---

## Brand & Style

The design system is built upon the philosophy of **Warm Minimalism and Sustainable Craft**. It targets a mindful audience that appreciates the slow, artisanal process of organic baking and cacao production. The emotional response should be one of tranquility, trustworthiness, and sensory warmth—evoking the smell of fresh pastry and the tactile nature of handmade goods.

The style is a blend of **Minimalism** and **Tactile** design. It utilizes expansive whitespace (the "air") to allow product photography to breathe, while employing subtle textures and soft shadows to prevent the UI from feeling sterile. Every digital touchpoint should feel as intentional and high-quality as a hand-wrapped box of chocolates.

## Colors

The palette is derived from natural, earth-borne ingredients. 
- **Base (Off-white/Ivory):** Used for the primary background to create an "airy" and paper-like feel, softer on the eyes than pure white.
- **Main (Chocolate Brown):** Used for primary brand elements, typography, and iconography to ensure depth and readability.
- **Secondary (Muted Pistachio):** Used for supporting elements, success states, or categories related to "organic" or "herbal" offerings.
- **Accent (Apricot Orange):** Reserved strictly for primary Call-to-Action (CTA) elements and high-priority notifications to provide a warm, sun-kissed contrast to the earthy base.

## Typography

This design system employs a sophisticated typographic pairing to reflect its "Craft" identity. **Playfair Display** provides an editorial, elegant serif feel for headings, suggesting heritage and quality. **Be Vietnam Pro** is used for body text and labels; its contemporary, friendly, and slightly rounded terminals harmonize with the organic brand concept while ensuring modern legibility.

Headlines should use tighter letter spacing to maintain a structured, premium look. Body copy requires generous line heights (1.6) to support the "airy" layout philosophy.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop to maintain a boutique, curated feel similar to a high-end magazine. On mobile, it transitions to a **Fluid Grid** to ensure accessibility.

- **Desktop:** 12-column grid with a 1200px max-width. Large 48px margins create a frame around the content.
- **Mobile:** 4-column grid. Margins are reduced to 20px, but vertical spacing between sections (padding-top/bottom) should remain generous (64px+) to maintain the sense of "air."
- **Rhythm:** All spacing (margins, padding, gaps) must be multiples of 8px to maintain a consistent visual beat.

## Elevation & Depth

Visual hierarchy in the design system is achieved through **Tonal Layers** and **Ambient Shadows**. 

Avoid heavy, black shadows. Instead, use "Soft Soil" shadows: low-opacity (#5D4037 at 8-12%) with a large blur radius (16px to 32px) and a slight vertical offset. This makes cards appear as though they are resting gently on a soft surface. 

Backgrounds may occasionally use a very subtle grain texture overlay (2% opacity) to mimic the feel of recycled paper or organic packaging, adding to the tactile experience.

## Shapes

The shape language is defined by **Rounded** corners (Level 2). This softens the "minimalist" edges, making the UI feel more approachable and organic. 

- **Components:** Standard buttons and input fields use a 0.5rem (8px) radius.
- **Containers:** Cards and large modal overlays use a 1rem (16px) radius.
- **Imagery:** Product photography should either be fully rectangular with sharp edges for an editorial look, or use a large 1.5rem radius to match the UI's softness.

## Components

### Buttons
- **Primary:** Warm Apricot (#F4A460) background with Chocolate Brown text. No border. Soft shadow on hover.
- **Secondary:** Chocolate Brown outline (1px) with transparent background.
- **Tertiary/Ghost:** Chocolate Brown text with an underline that appears on hover.

### Cards
Cards should use the Ivory base (#F9F7F2) or a pure white fill, with a 1px border in a lightened version of the Chocolate Brown (e.g., 10% opacity). They should utilize the "Soft Soil" shadow to lift from the background.

### Input Fields
Inputs are minimalist: a 1px bottom border in Chocolate Brown or a fully enclosed light-grey stroke. Labels are consistently `label-md` and placed above the field.

### Chips & Tags
Used for dietary labels (e.g., "Vegan," "Gluten-Free"). These use the Muted Pistachio (#8DA399) as a soft background tint with dark green or brown text.

### Lists
Lists should be separated by thin, light horizontal rules (1px) to maintain order without adding visual bulk. Use the serif `headline-md` for list item titles to maintain elegance.