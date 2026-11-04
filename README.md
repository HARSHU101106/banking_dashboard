# Banking Products Dashboard

A single-screen dashboard that brings savings, credit card, loan and wealth products into one unified view.

## Technology

Plain **HTML, CSS and vanilla JavaScript** in one file (`Banking_Products_Dashboard.html`), with a warm neutral palette and no framework or build step.

## How to run

Open `Banking_Products_Dashboard.html` in a browser.

## What the screen shows

- **Summary row:** total products, active products, items needing attention, and savings and investment count.
- **Product cards:** name, category, status badge, short description, key metrics and a call-to-action button.
- **Details dialog:** opens from each card for extra product information.
- **Filters:** category tabs, a search box, and a status selector that work together.

## Code structure

The file has three clearly separated layers:

| Layer | What it contains |
| ----- | --------------- |
| CSS   | Design tokens and component styling, including warm ivory, taupe, and beige surfaces |
| Data  | `PRODUCT_DATA` and `fetchProducts()`, which simulate the product API |
| UI    | Render functions for stats, tabs, cards, filters, and the details dialog |

The UI renders data from `fetchProducts()` rather than storing product records directly, keeping logic and presentation separate.

## Colour theme

The dashboard uses a warm, neutral palette to match the current HTML design:

| Colour | Hex | Used for |
| ------ | --- | -------- |
| Warm Taupe | `#9A8472` | borders, accents, and logo sheen |
| Sandy Beige | `#C8B39A` | soft glow and warm highlights |
| Oatmeal | `#E0D1B8` | background glow and hover states |
| Vanilla Cream | `#EFE3CE` | metric tiles and icon chips |
| Soft Linen | `#F6F0E6` | surfaces and tab containers |
| Ivory | `#FAF7F2` | page background, cards, and dialog panels |

Text and primary action elements use a deeper brown (`#6B5646`) and cocoa (`#3A2E25`) for contrast on the light ivory surfaces.

## Usability and accessibility

- Responsive grid that adapts from desktop to phone width
- Controls are labelled, touch-friendly, and keyboard accessible with a visible focus ring
- Status is conveyed with text and badge styling, not colour alone
- Reduced-motion preferences are respected
