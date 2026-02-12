# TERROIR — Specialty Coffee

Elegant, single-page specialty coffee site with editorial typography, a warm “paper + ink” palette, and a premium product/story layout.

## Highlights
- Responsive landing page (desktop + mobile nav)
- Smooth in-page scrolling
- Tailwind (CDN) with a custom coffee/cream/forest color system
- Texture overlay + subtle image grain and motion
- Lucide icons + Google Fonts (Cormorant Garamond, Source Serif 4)

## Project Structure
- `index.html` — Page layout + Tailwind theme config
- `style.css` — Texture + animations + small custom styles
- `script.js` — Mobile menu + smooth scrolling + icon init

## Run Locally
This is a static site—no build step required.

Option A (quick):
- Open `index.html` in your browser

Option B (recommended):
- Use VS Code “Live Server” (or any local static server) and open the served URL

## Customize
- Colors / fonts: edit the `tailwind.config` block in `index.html`
- Sections: update IDs (`#origins`, `#process`, `#journal`, `#subscribe`) to match your nav links
- Images: placeholder images currently load from `picsum.photos`—swap to your own assets/URLs for production

## Deployment
Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages):
- Upload `index.html`, `style.css`, and `script.js`

## Credits
- Tailwind CSS (CDN)
- Lucide Icons
- Google Fonts

## Notes
- This repo does not currently include a license file. Add one if you plan to publish or accept contributions.
