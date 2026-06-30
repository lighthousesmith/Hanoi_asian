---
name: Urban Hanoi Street
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#3d4a3f'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#6d7a6e'
  outline-variant: '#bccabc'
  surface-tint: '#006d3a'
  primary: '#006d3a'
  on-primary: '#ffffff'
  primary-container: '#32b86c'
  on-primary-container: '#004220'
  inverse-primary: '#5fde8e'
  secondary: '#5d5f5d'
  on-secondary: '#ffffff'
  secondary-container: '#e2e3e1'
  on-secondary-container: '#636563'
  tertiary: '#a7354a'
  on-tertiary: '#ffffff'
  tertiary-container: '#fd778a'
  on-tertiary-container: '#720a26'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7cfba7'
  primary-fixed-dim: '#5fde8e'
  on-primary-fixed: '#00210d'
  on-primary-fixed-variant: '#00522a'
  secondary-fixed: '#e2e3e1'
  secondary-fixed-dim: '#c6c7c5'
  on-secondary-fixed: '#1a1c1b'
  on-secondary-fixed-variant: '#454746'
  tertiary-fixed: '#ffdadc'
  tertiary-fixed-dim: '#ffb2b9'
  on-tertiary-fixed: '#400010'
  on-tertiary-fixed-variant: '#871d34'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Anton
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Anton
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.2'
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
  label-bold:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
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
  gutter: 20px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style
The brand personality is energetic, rhythmic, and unapologetically bold, capturing the organized chaos of a modern Vietnamese street market. It targets a youthful, food-loving demographic that values speed and authenticity. 

The design style is **Modern Urban**, blending high-fidelity cleanliness with a "Street 3D" aesthetic. We utilize layered depth and floating elements to create a sense of physical space. While the typography is heavy and impactful, the interface remains airy and accessible through generous whitespace and a "paper-on-pavement" layering logic.

## Colors
The palette is built on the contrast between the fresh **Vibrant Green** (Primary) and a warm **Light Surface** (Secondary) that mimics clean paper packaging. 

- **Primary (#32b86c):** Used for calls to action, active states, and brand-critical highlights.
- **Surface (#f9f9f7):** The foundational background color to keep the UI bright and appetizing.
- **Deep Charcoal (#1a1a1a):** High-contrast text and heavy shadows for maximum readability and "urban" punch.
- **Signal Yellow (#ffcc00):** A secondary accent for badges, ratings, and "New" tags to mimic street signage.

## Typography
The typography strategy relies on the tension between the loud, condensed **Anton** for headlines and the friendly, contemporary **Be Vietnam Pro** for functional text.

Headlines should always be uppercase or title case to maintain the "street sign" impact. Use `display-lg` for hero sections and promotional banners. `body-lg` is the standard for item descriptions to ensure comfort during browsing. All labels and functional UI text (prices, calories, categories) use **Be Vietnam Pro** with increased tracking for clarity.

## Layout & Spacing
The layout follows a **Fluid Grid** model with high-density spacing to reflect urban efficiency.

- **Desktop:** 12-column grid with a 1200px max-width container.
- **Mobile:** 4-column grid with tight 16px side margins.
- **Rhythm:** Use an 8px base unit. Component internal padding should favor `sm` (12px) for a compact, "packed" feel, while section margins should use `lg` (48px) to provide breathability between content blocks.

## Elevation & Depth
To achieve the "3D Urban" aesthetic, this design system rejects flat design in favor of **Layered Shadows**.

- **Level 1 (Surface):** The `#f9f9f7` background.
- **Level 2 (Cards):** Low-offset, crisp shadows (e.g., `0px 4px 0px rgba(26,26,26,0.1)`) to create a "sticker" or "cut-out" effect.
- **Level 3 (Interactive/Floating):** High-offset, multi-layered shadows. When a user hovers over a food card or button, it should "lift" (e.g., `0px 12px 24px rgba(26,26,26,0.12)`).
- **Hard Borders:** Use 2px solid Deep Charcoal borders on primary buttons and input fields to ground the 3D elements.

## Shapes
Shapes are **Rounded** but structured. The standard 0.5rem (8px) corner radius provides a modern, friendly feel without becoming too "bubbly" or "childish." 

- **Cards & Inputs:** 0.5rem (8px).
- **Large Banners:** 1rem (16px).
- **Floating Action Buttons:** 1.5rem (24px) or fully pill-shaped to distinguish from content containers.

## Components

- **Buttons:** Primary buttons use a thick 2px charcoal border, a solid Brand Green background, and white Anton text. On click, they shift down 2px to simulate a physical press.
- **Cards:** Food cards use the light surface color with a subtle 1px border. The price is always displayed in a high-contrast floating badge in the top-right corner.
- **Chips/Filters:** These mimic street tape or stickers. They should be pill-shaped with a light grey background, moving to Brand Green with a 3D shadow when active.
- **Input Fields:** Heavy 2px charcoal borders with `Be Vietnam Pro` labels positioned above the field. No placeholder text; use floating labels for a cleaner look.
- **Lists:** Order lists and menus use a "Ticket" aesthetic—perforated edge dividers (visual only) and bold prices.
- **Sticky Cart:** A floating bar at the bottom of the mobile screen using a level-3 shadow to appear as if it is hovering over the content.