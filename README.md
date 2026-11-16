# Walk-in Store Template

An animated storefront: doors open on scroll, a tappable floor plan, a scrolling aisle, and a checkout counter.

## Make your own store
1. Click **Use this template** (top of this repo) to create your copy.
2. Open `index.html` and edit only the block marked `STORE CONFIG` near the top:
   - `name`, `tagline`, and the text lines
   - `colors` (hex codes)
   - `sections` and their `items` (name, price, optional `image` link)
   - `whatsapp` and `email`: where orders are sent. At checkout, the bag becomes a pre-filled message with items and total. Leave either empty to hide that button.
3. Commit your changes.

## Publish
Repo **Settings → Pages → Deploy from a branch → `main` / `(root)` → Save**.
Your link: `https://yourusername.github.io/repo-name` (or `yourusername.github.io` if the repo is named that).

## Notes
- Up to 4 sections fit the floor plan; give each 1 to 4 items.
- Images must be web links (e.g. hosted in the repo as `images/shirt.jpg`).
- Animation libraries load from public CDNs, so visitors need an internet connection.
