---
name: StockQuick Merchant Design System
colors:
  surface: '#f8f9ff'
  surface-dim: '#d0dbed'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dee9fc'
  surface-container-highest: '#d9e3f6'
  on-surface: '#121c2a'
  on-surface-variant: '#404945'
  inverse-surface: '#27313f'
  inverse-on-surface: '#eaf1ff'
  outline: '#707975'
  outline-variant: '#bfc9c4'
  surface-tint: '#326859'
  primary: '#003329'
  on-primary: '#ffffff'
  primary-container: '#114b3e'
  on-primary-container: '#83baa9'
  inverse-primary: '#9ad2c0'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#412600'
  on-tertiary: '#ffffff'
  tertiary-container: '#5f3a00'
  on-tertiary-container: '#f29c06'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b6eedc'
  primary-fixed-dim: '#9ad2c0'
  on-primary-fixed: '#002019'
  on-primary-fixed-variant: '#174f42'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#121c2a'
  surface-variant: '#d9e3f6'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 24px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 22px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style

This design system is engineered for micro-retailers, neighborhood grocery stores, and corner markets who require rapid, error-free operational tools during peak trading hours. 

The aesthetic is functional, crisp, and approachable. It fuses modern SaaS utility with tactile grocery-retail ergonomics:
- **Visual Personality:** Dependable, clear, efficient, and dignified. It avoids intimidating enterprise complexity in favor of straightforward, high-legibility affordances.
- **Emotional Response:** Inspires quiet confidence, speed, and absolute control over stock and daily pricing without visual fatigue.
- **Design Philosophy:** Minimalist utility enhanced with soft depth. High-contrast labels ensure legibility under harsh shop lights or low-grade tablet screens, paired with forgiving touch targets suited for rapid counter use.

## Colors

The palette balances administrative authority with active operational feedback:

- **Primary (`#114B3E` - Forest Green):** Anchors core actions, navigation headers, primary triggers, and high-level inventory totals. Establishes trustworthiness, wealth preservation, and mercantile solidity.
- **Secondary (`#10B981` - Emerald Green):** Used for positive states, in-stock confirmation badges, price check successes, and active growth metrics.
- **Tertiary (`#F59E0B` - Amber Glow):** Dedicated to attention-sensitive states: critical low stock alerts, pending orders, and restock prompts.
- **Neutral (`#1F2937` - Charcoal Dark):** Ensures primary typography, product SKUs, and numerical pricing retain maximum optical contrast.
- **Surfaces & Canvases:** The main background rests on a cool neutral canvas (`#F8F9FA`), elevating pure white cards (`#FFFFFF`) via soft dimensional layers rather than heavy line work.
- **Muted Borders:** Structured lines use a soft slate tint (`#E5E7EB`) to define structural boundaries without visual noise.

## Typography

**Plus Jakarta Sans** is selected across all roles for its balanced geometric clarity and open counters. This geometry facilitates rapid scanning of product names, barcodes, quantity indicators, and currency figures on varying display qualities.

- **Numerals & Prices:** Use tabular numerals where possible in inventory tables and point-of-sale breakdowns.
- **Hierarchical Balance:** Product titles use `title-lg` or `title-md` with semi-bold weights to guarantee scanability against fast eye movements.
- **Labels & Microcopy:** Stock status tags and category pills use `label-md` and `label-sm` with slight positive letter spacing to maintain clarity even at reduced sizes.

## Layout & Spacing

The layout employs an adaptable fluid grid tailored to dynamic retail workflows, moving effortlessly between desktop counter setups and mobile stockroom scanning:

- **Mobile Viewports (< 768px):** 4-column layout with `margin-mobile` (16px) and `gutter-mobile` (12px). Dense list views take precedence over grid cards to maximize vertical real estate.
- **Tablet Viewports (768px - 1024px):** 8-column layout with 20px gutters. Optimized for horizontal tablet checkout stands with side-by-side catalog and cart drawers.
- **Desktop Viewports (> 1024px):** 12-column layout capped at a max-width container of 1440px with `margin` (32px) and `gutter` (20px). Supports persistent navigation and expansive inventory data sheets.
- **Rhythm & Touch Areas:** All clickable UI elements (product rows, quantity steppers, quick-filter chips) must enforce a minimum hit target of 44px on touch screens, buffered by `space-sm` and `space-md` gaps.

## Elevation & Depth

This design system uses a low-intensity, diffuse shadow approach layered over subtle neutral borders to avoid visual heaviness:

- **Level 0 (Flat / Canvas):** Applied to the main dashboard background (`#F8F9FA`).
- **Level 1 (Card & Content Blocks):** Pure white background (`#FFFFFF`), a hairline border (`1px solid #E5E7EB`), and an ambient shadow: `0 1px 3px 0 rgba(17, 75, 62, 0.04), 0 1px 2px -1px rgba(0, 0, 0, 0.04)`.
- **Level 2 (Interactive Cards & Dropdowns):** Subtle hover lifts on product grid items and active select menus: `0 4px 6px -1px rgba(17, 75, 62, 0.07), 0 2px 4px -2px rgba(0, 0, 0, 0.05)`.
- **Level 3 (Modals, Slide-overs, & Sticky Footers):** Floating action bars, SKU barcode scanners, and modal overlays: `0 12px 24px -4px rgba(17, 75, 62, 0.12), 0 4px 8px -2px rgba(0, 0, 0, 0.06)`. Tinting shadows slightly with the primary green preserves cohesive warmth and prevents dull muddy grays.

## Shapes

The shape system adopts a friendly, contemporary contour profile with a baseline factor of `2`:

- **Containers & Product Cards:** Enforce `rounded-xl` (1.5rem / 24px) for expansive hero blocks and primary cards, providing a modern, tactile framing to inventory elements.
- **Standard Controls:** Input boxes, buttons, quantity pickers, and alerts use standard rounded tokens (0.5rem to 0.75rem / 8px - 12px).
- **Status Pills & Counters:** Employ fully rounded (pill-style) geometries for tags such as stock status, category identifiers, and item count notifications.

## Components

### Buttons
- **Primary:** Solid `#114B3E` background, pure white text, font weight `600`, 0.75rem border radius. Hover state transitions to `#0A332A`. Active state scales subtly (98%).
- **Secondary:** Transparent background with a `1.5px` border in `#114B3E` and text in `#114B3E`.
- **Accent / Low-Stock Action:** Solid amber `#F59E0B` with white or dark charcoal text for high-urgency restock ordering.
- **Touch Target:** Minimum height is 44px on mobile devices, with horizontal padding set to `space-lg`.

### Cards & Inventory Tiles
- **Product Card:** White canvas (`#FFFFFF`), `rounded-xl` curvature, hairline perimeter border (`#E5E7EB`), and Level 1 elevation.
- **Media Presentation:** Product thumbnails fill a dedicated top container with an integrated aspect ratio (1:1 or 4:3) with a neutral soft gray background (`#F3F4F6`).
- **Data Arrangement:** Product name sits prominent at `title-md`, price in large dark numerals, and a stock tag anchored at the bottom-right corner.

### Chips & Stock Badges
- **In Stock:** Soft emerald tint background (`#ECFDF5`), bold emerald text (`#065F46`), pill-shaped.
- **Low Stock:** Soft amber tint background (`#FFFBEB`), warm amber text (`#92400E`), pill-shaped with optional warning icon.
- **Out of Stock:** Soft rose tint background (`#FEF2F2`), red text (`#991B1B`).

### Input Fields & Search Bars
- **Catalog Search:** Prominent 48px height, rounded-xl styling, white fill, 1px border (`#D1D5DB`), leading search icon, and a quick-clear trailing button.
- **Focus State:** 2px ring in primary `#114B3E` with a subtle green-tinted glow and zero layout shift.
- **Barcode / SKU Input:** Monospaced styling support with a dedicated camera-scan trigger icon button embedded inside the right edge.

### Lists & Inventory Rows
- **List Items:** Separated by soft 1px dividers (`#F3F4F6`). Minimum row height of 56px to ensure touch accuracy.
- **Inventory Meta:** Product SKU and unit types displayed in `body-sm` (`#6B7280`), price and stock count aligned right in tabular format.

### Quantity Stepper (POS & Restock)
- **Inline Stepper:** Segmented pill with minus (`-`), numeric value, and plus (`+`) buttons. High tactile contrast with tactile tap feedback to minimize miscounts during fast transactions.