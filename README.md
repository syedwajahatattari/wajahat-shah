# EcomXperts Shopify Hiring Task — Dawn Theme

This repository contains the completed submission for the **EcomXperts Shopify Developer Hiring Task**.

## What's Inside

A customized **Dawn** theme (Shopify 2.0) pulled from the test store, with two custom sections added:

### `sections/hero-banner.liquid`
A full-width hero banner section featuring:
- Desktop and mobile image support with responsive layout
- Customizable heading, subheading, and CTA button (text + URL)
- Accessible markup (single visible `<h1>`, proper ARIA attributes)
- Performance-conscious CSS (specific `transition` properties, no `transition: all`)
- Scoped styles via `{%- style -%}` with Google Fonts import
- Vanilla JS for mobile menu toggle — strict mode, `const`/`let`, fully commented

### `sections/product-grid.liquid`
A lookbook-style product grid section featuring:
- Hotspot pins overlaid on a lifestyle image — each pin links to a product popup
- Product variant selector (color swatches + size dropdown)
- Bundle add-on upsell triggered by color/size combination
- Shopify AJAX Cart API (`/cart/add.js`) integration
- Fully accessible modal: focus trap, `role="dialog"`, `aria-live` status region
- Memory-safe event listeners (AbortController, debounced resize handler)
- No `alert()` — inline error display with `role="alert"`

## Store Preview

Live draft theme preview (Dawn — unpublished):  
`https://admin.shopify.com/store/ecomxpertstest/themes/191090884976/editor`

## Task Requirements Checklist

- [x] Pull Dawn theme from given Shopify store
- [x] Create `hero-banner.liquid` section
- [x] Create `product-grid.liquid` section
- [x] Code is optimized, performant, and responsive
- [x] Code is well-commented and accessible (WCAG AA target)
- [x] Git repository initialized and pushed to GitHub
- [x] Changes pushed to draft Dawn theme (not the live theme)
- [x] No other theme files were modified
