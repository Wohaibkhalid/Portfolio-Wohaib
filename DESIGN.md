---
name: Executive Legacy
colors:
  surface: '#111415'
  surface-dim: '#111415'
  surface-bright: '#37393b'
  surface-container-lowest: '#0c0f10'
  surface-container-low: '#191c1e'
  surface-container: '#1d2022'
  surface-container-high: '#282a2c'
  surface-container-highest: '#323537'
  on-surface: '#e1e2e4'
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#e1e2e4'
  inverse-on-surface: '#2e3132'
  outline: '#8f9097'
  outline-variant: '#45464d'
  surface-tint: '#bdc6e1'
  primary: '#bdc6e1'
  on-primary: '#273045'
  primary-container: '#0a1428'
  on-primary-container: '#757f97'
  inverse-primary: '#555e76'
  secondary: '#e9c176'
  on-secondary: '#412d00'
  secondary-container: '#604403'
  on-secondary-container: '#dab36a'
  tertiary: '#c3c6cd'
  on-tertiary: '#2d3136'
  tertiary-container: '#11151a'
  on-tertiary-container: '#7b7f85'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d9e2fe'
  primary-fixed-dim: '#bdc6e1'
  on-primary-fixed: '#121b2f'
  on-primary-fixed-variant: '#3d475d'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e0e2e9'
  tertiary-fixed-dim: '#c3c6cd'
  on-tertiary-fixed: '#181c21'
  on-tertiary-fixed-variant: '#43474d'
  background: '#111415'
  on-background: '#e1e2e4'
  surface-variant: '#323537'
  deep-navy: '#0A1428'
  heritage-gold: '#C5A059'
  charcoal-slate: '#1E2227'
  platinum-gray: '#E2E4E9'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 84px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  quote:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 36px
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
  gutter: 32px
  margin-mobile: 24px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The visual narrative of this design system is rooted in **Modern Prestige**. It balances the weight of institutional authority with the clarity of contemporary digital design. The system is designed to evoke trust, influence, and quiet confidence, moving away from generic corporate aesthetics toward a curated, editorial experience.

The design style utilizes **Minimalism** with **High-Contrast** accents. It prioritizes:
- **Presence over Clutter:** Utilizing generous whitespace to allow high-impact content to breathe.
- **Editorial Authority:** Leveraging dramatic typographic scales and intentional alignment.
- **Sophisticated Textures:** Using deep tonal layers and subtle metallic highlights rather than flat colors.
- **Architectural Structure:** A rigorous adherence to a grid that reflects stability and precision.

This system targets high-level stakeholders, community leaders, and international partners, ensuring that the visual interface is as professional and refined as the individual it represents.

## Colors

The palette is designed for high-contrast impact and a premium feel. 

- **Primary (Deep Navy):** A sophisticated, near-black blue used for primary backgrounds and deep structural elements. It provides more depth than pure black while maintaining maximum authority.
- **Secondary (Heritage Gold):** A refined, muted metallic used for accents, call-to-actions, and highlights. It signifies excellence and philanthropic value.
- **Tertiary (Charcoal Slate):** Used for card backgrounds, borders, and secondary surfaces to create depth without sacrificing the dark-mode aesthetic.
- **Neutral (Platinum & Snow):** Used exclusively for typography and subtle UI icons to ensure WCAG AA readability against dark backgrounds.

The default mode is **Dark**, reinforcing the premium "executive" aesthetic, though the typography system is robust enough to support a high-contrast light-mode variant for official documentation if required.

## Typography

This design system uses a high-contrast typographic pairing to establish a clear hierarchy between heritage and utility.

**Playfair Display** is the signature serif. It is used for headlines and display text to convey prestige and tradition. Tighten letter-spacing on larger sizes for a more "locked-in" editorial look.

**Inter** provides a clean, functional counterpoint. Its high x-height and neutral character make it ideal for dense information, body copy, and UI labels. 

**Usage Guidelines:**
- **Headlines:** Always use Playfair Display. Use high-contrast sizing (e.g., a massive Display LG followed by a small Label Caps) to create a sophisticated rhythm.
- **Body:** Use Inter for all reading text. Keep line lengths between 60-75 characters for optimal legibility.
- **Interactive Labels:** Use Inter Medium or Semi-Bold in uppercase with tracked-out letter spacing for a modern, architectural feel.

## Layout & Spacing

The layout philosophy is based on a **Fixed Grid** with generous, intentional whitespace. 

**Grid Structure:**
- **Desktop:** A 12-column grid with a 1280px max-width container. 32px gutters provide ample breathing room between content modules.
- **Tablet:** An 8-column grid with 24px gutters.
- **Mobile:** A 4-column grid with 16px gutters and 24px side margins.

**Spacing Rhythm:**
- Use a base unit of **8px**. 
- **Section Gaps:** Vertical spacing between major sections should be significant (80px to 120px) to force focus on one narrative block at a time.
- **Alignment:** Consistent left-alignment is preferred for long-form content to maintain an authoritative, structured appearance.

## Elevation & Depth

Visual hierarchy is conveyed through **Tonal Layers** and **Low-Contrast Outlines**. In this design system, shadows are used sparingly to avoid a "cheap" or overly digital look.

- **Surface Levels:** 
  - Level 0 (Base): Deep Navy (#0A1428)
  - Level 1 (Cards/Nav): Charcoal Slate (#1E2227)
  - Level 2 (Modals/Popovers): A slightly lighter tint of slate with a subtle Heritage Gold border.
- **Outlines:** Use 1px solid borders in Charcoal Slate or 10% opacity Gold to define shapes without the visual weight of shadows.
- **Shadows:** When necessary, use "Ambient Shadows"—extremely soft, large-radius blurs (40px+) with low opacity (15%) and a slight navy tint to ground floating elements.
- **Image Treatments:** All photography should have a consistent grade (slight desaturation or high-contrast clarity) to match the premium color palette.

## Shapes

The shape language is **Soft (0.25rem)**. 

This system avoids perfectly sharp corners to appear approachable, but also avoids highly rounded or pill-shaped elements which can feel too casual or "tech-startup." The subtle 4px radius on buttons and cards provides a polished, high-end manufacturing feel, reminiscent of luxury watchmaking or premium stationery.

- **Primary Buttons:** 4px radius.
- **Content Cards:** 8px (rounded-lg) for a more substantial container feel.
- **Media Containers:** 4px radius to keep the focus on the content.

## Components

### Buttons
- **Primary:** Heritage Gold background with Deep Navy text. 4px radius. No shadow, bold Inter typography.
- **Secondary:** Transparent background with a 1px Heritage Gold border and Gold text. 
- **Tertiary/Ghost:** Platinum text with no border, becoming gold on hover.

### Cards
- Surfaces should use the Charcoal Slate background. 
- Use a 1px border of #FFFFFF at 5% opacity to provide a subtle edge definition against the navy background.
- Typography within cards should maintain high contrast (Platinum for titles, 70% opacity Platinum for body).

### Input Fields
- Dark backgrounds (Deep Navy) with a subtle bottom-border or thin outline in Charcoal Slate. 
- Active state should transition the border color to Heritage Gold.

### Lists & Navigation
- Navigation items use Inter in uppercase (Label-Caps) with high letter spacing.
- Use a Heritage Gold "underline" or "dot" indicator for active states.

### Professional Image Treatments
- All images should feature a subtle "vignette" or overlay to ensure white text remains legible when placed over photography.
- Incorporate the "AS" monogram as a watermark or stylistic element in the corner of significant media blocks.