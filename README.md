# Marginalia — Books, Secondhand and New

A single-page demo storefront for a fictional neighborhood bookshop, **Marginalia** (No. 14 Thistle Row, est. 2011). Built as a self-contained `index.html` with no build step, no backend, and no real payments — everything runs client-side.

## Features

- **Home page** — hero section, staff picks, department shelf, and "new on the shelf" restocks
- **Shop all** — full catalog with:
  - Department / category filters
  - Condition filters (New, Like New, Good, Well-read)
  - Price filters (Under $10, $10–$20, Over $20)
  - Sort (Featured, Price low–high/high–low, Title A–Z)
  - Wishlist toggle ("Show saved only")
- **Product detail** — quantity picker, add to cart, related titles ("You might also like")
- **Cart drawer** — slide-out cart with subtotal, editable quantities
- **Checkout** — shipping address form, payment fields (demo only, no data sent/stored), order summary with subtotal/shipping/tax/total, and an order confirmation screen
- **Orders page** — history of orders placed on the current device (stored locally in-browser)
- **Wishlist** — save/unsave books via a heart icon on each cover
- **Search** — quick search bar in the top nav
- **Shop assistant chat widget** — a simple chat launcher/window UI
- **Newsletter signup** — "One good line, weekly" email capture
- **Offline banner** — shown when the browser has no connection
- **Responsive nav** — mobile hamburger menu alongside the desktop nav

## Tech

- Plain HTML/CSS/JS — no frameworks, no dependencies to install
- Google Fonts: Fraunces (display), Literata (body/serif), IBM Plex Mono (UI/labels)
- Client-side state only — cart, wishlist, and orders persist per-browser (not synced to a server)

## Design

- Warm, literary aesthetic — parchment background, ink/rust/brass color palette
- Deliberately "secondhand bookshop" tone throughout copy (e.g., condition labels like *Well-read*, trade-in messaging, a reading room upstairs)

## Running it

No build tools needed. Just open `index.html` in a browser.

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

- This is a **demo storefront** — checkout does not process real payments, and no card details are transmitted or stored anywhere.
- Cart, wishlist, and order history live only in the visiting browser/device and are not shared across devices or synced to any server.# books-task-2
A demo storefront for a neighborhood bookshop, Marginalia. Browse secondhand and new books by department, filter by condition and price, add to cart, checkout, and track orders — all in-browser. Includes wishlist, search, staff picks, and a shop assistant chat. Built as a design/dev demo, no real payments processed."
