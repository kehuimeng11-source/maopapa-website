# MAOPAPA website

A calm, elevated pet-lifestyle storefront for cat and dog households.

## Included modules

1. **Home Hero** — responsive navigation, editorial hero image, and brand-principles strip.
2. **Product Card Collection** — three responsive product cards with product data and Quick Add controls.
3. **Shopping Bag Drawer** — an accessible slide-in bag with item removal, subtotal calculation, overlay dismissal, and Escape-key close behavior.

## Preview

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Netlify deployment

Connect this GitHub repository to Netlify, use publish directory `.` and leave the build command empty. Every push to `main` deploys the static page automatically. Tailwind CSS loads from its CDN, so no dependency install or build step is required.
