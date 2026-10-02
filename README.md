# Flipkart Clone (Single-File E-commerce UI)

A single-file e-commerce storefront UI inspired by Flipkart — product grid, categories, search bar, cart drawer and checkout-style layout. Hindi-language interface, pure static HTML, no build step.

## Features

- Flipkart-style header with search and category navigation
- Product cards with prices, discounts and ratings
- Cart drawer with add/remove and totals
- Responsive layout (Tailwind CSS), Font Awesome icons
- All client-side — demo catalog data embedded in the file

## Tech stack

- Single HTML file (`index.html`) — HTML5, CSS3, vanilla JavaScript
- Tailwind CSS and Font Awesome via CDN

## Quick start

Open `index.html` in a browser (needs internet for the CDNs):

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Project structure

```
Flipkart/
├── index.html                     # the whole storefront (single file)
├── "Flipkart जैसी वेबसाइट 🌐.html"  # original uploaded copy
├── README.md
└── LICENSE
```

## Deploy notes

Static file — deployed to GitHub Pages. No build, no environment variables. Demo data only; no real checkout or backend.

## License

Free to use.

---

Built by Girish Lade — [ladestack.in](https://ladestack.in)
