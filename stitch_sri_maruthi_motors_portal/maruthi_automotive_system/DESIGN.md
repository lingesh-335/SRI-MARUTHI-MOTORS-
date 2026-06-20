---
name: Maruthi Automotive System
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daea'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eefe'
  surface-container-high: '#e2e8f8'
  surface-container-highest: '#dce2f3'
  on-surface: '#151c27'
  on-surface-variant: '#5d3f3e'
  inverse-surface: '#2a313d'
  inverse-on-surface: '#ebf1ff'
  outline: '#916e6d'
  outline-variant: '#e6bdbb'
  surface-tint: '#bf0029'
  primary: '#b90027'
  on-primary: '#ffffff'
  primary-container: '#e31837'
  on-primary-container: '#fffaf9'
  inverse-primary: '#ffb3b1'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2e1'
  on-secondary-container: '#656464'
  tertiary: '#595b5d'
  on-tertiary: '#ffffff'
  tertiary-container: '#727476'
  on-tertiary-container: '#fafbfd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410007'
  on-primary-fixed-variant: '#92001d'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e1e2e4'
  tertiary-fixed-dim: '#c5c6c8'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f9f9ff'
  on-background: '#151c27'
  surface-variant: '#dce2f3'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
  headline-md-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 0.5rem
  sm: 1rem
  md: 1.5rem
  lg: 2.5rem
  xl: 4rem
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  max-width: 1280px
---

## Brand & Style

The design system is engineered to evoke the precision and reliability of the automotive industry. The brand personality is authoritative yet accessible, positioning the dealership as a high-trust partner in the customer's vehicle ownership journey. 

The aesthetic follows a **Modern Corporate** direction with subtle **Minimalist** influences. It prioritizes clarity and speed, reflecting the performance of the vehicles. Visuals are characterized by high-contrast intersections of red and black, expansive whitespace to ensure legibility on mobile devices, and a focus on functional elegance. The interface avoids unnecessary decoration, relying instead on strong typography and structural integrity to communicate professionalism.

## Colors

The palette is anchored by a high-energy **Primary Red**, used strategically for calls to action, brand highlights, and critical interactive states. **Secondary Black** provides the structural foundation, used for typography and deep-contrast backgrounds in hero sections.

- **Primary (#E31837):** Used for primary buttons, active states, and brand marks.
- **Secondary (#111111):** Applied to headings, navigation backgrounds, and hero overlays to provide depth and a premium feel.
- **Neutral/Surface (#F3F4F6):** A light gray used for background grouping and subtle component borders.
- **White (#FFFFFF):** The primary workspace color to maintain a clean, high-trust clinical feel.
- **Supportive Neutrals:** Mid-grays are reserved for secondary text and disabled states.

## Typography

This design system utilizes **Inter** exclusively to ensure a systematic and utilitarian feel across all touchpoints. The typographic hierarchy relies on heavy weights (Bold and ExtraBold) for headlines to mimic automotive signage and branding.

Body text is kept clean with ample line height to ensure readability during mobile browsing. Labels and technical specifications should use the `label-md` style with uppercase tracking to differentiate data-heavy content from narrative content.

## Layout & Spacing

The layout is built on a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

- **Mobile-First:** Navigation and key actions are optimized for thumb-reach. 
- **Sticky Navigation:** The main header remains fixed at the top with a slight backdrop blur or solid black background to ensure brand presence is never lost.
- **Spacing Rhythm:** Use a 4px baseline. Components are separated by `lg` (40px) or `xl` (64px) units to maintain a spacious, premium feel. 
- **Hero Sections:** Utilize full-bleed widths with centered or left-aligned content overlays.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Low-Contrast Outlines** rather than heavy shadows. 

- **Surface Levels:** The primary background is White. Secondary information sits on Light Gray (#F3F4F6) containers.
- **Hero Depth:** Dark-overlay heroes use a 40-60% black opacity gradient over high-quality vehicle photography to ensure text legibility.
- **Interactive Elevation:** Elements like vehicle cards use a very subtle, diffused shadow (0px 4px 20px rgba(0,0,0,0.05)) that intensifies slightly on hover to signal interactivity.
- **Borders:** Use 1px solid borders in #E5E7EB for input fields and card outlines to maintain a crisp, engineered look.

## Shapes

The shape language is **Soft (0.25rem)**. This subtle rounding suggests modern precision without being overly playful or organic. 

- **Buttons & Inputs:** Use the standard 0.25rem (4px) radius.
- **Cards:** Use the `rounded-lg` (8px) radius to create a distinct containerized look for vehicle listings.
- **Icons:** Use Lucide icons with a 2px stroke width to match the weight of the Inter typeface. Icons should always be used at 20px or 24px sizes.

## Components

- **Buttons:** 
    - *Primary:* Solid Red (#E31837) with White text. High-contrast.
    - *Secondary:* Solid Black or Outline Black.
    - *Hover:* Primary buttons shift 10% darker on hover; secondary buttons fill with a light gray tint.
- **Cards (Vehicle Listing):** White background, 1px border, 8px radius. Image at the top, followed by a title, price in Bold, and a "View Details" primary button. Hover effect includes a slight lift and shadow deepening.
- **Sticky Navigation:** Secondary Black (#111111) background. White logo on the left, Lucide "Menu" icon on the right for mobile, or simple text links for desktop.
- **Forms:** Sleek, minimalist inputs with 1px gray borders. Focus state uses a 2px Red border. Labels use `label-md` for a professional, technical appearance.
- **Hero Section:** Full-width container with a dark image background. Use `display-lg` for headlines and a single, high-contrast primary call-to-action button.
- **Chips/Badges:** Small, 4px rounded rectangles used for "New Arrival" or "In Stock" tags. Use light red backgrounds with dark red text for high visibility.