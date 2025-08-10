- 👋 Hi, I’m @Melson raven
- 👀 I’m interested in character art and story
- 🌱 I’m currently learning nothing yet
- 💞️ I’m looking to collaborate with the Big 5
- 📫 How to reach me melsonraven88@gmail.com
# Laxmie Saga — Static Website

This folder contains a ready-to-host static site for **Laxmie Saga**.  
Open `index.html` locally, or deploy to any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages).

## Structure
- `index.html` — Single-page site with sections for Characters, Spirits, Factions, Places, Gallery, and About.
- `styles.css` — Responsive, dark-themed design using modern CSS.
- `data.js` — Canonical data pulled from your notes (safe to edit).
- `app.js` — Client-side rendering (no frameworks).
- `assets/images/` — Replace the placeholder SVGs with your artwork/photos.

## Customize
- Edit `data.js` to add characters, spirits, places, and gallery items.
- Images: put files in `assets/images/` and update the `img`/`src` fields.
- Colors: tweak CSS variables at the top of `styles.css`.

## Deep Links
You can link directly to a character modal with a hash:  
`#characters:<id>` (e.g., `#characters:laxmie`).

## Local Preview
Just open `index.html` in a browser. For best results (and to avoid any CORS weirdness for images), serve with a simple local server:

Python 3:
```
python -m http.server 8080
```
Then visit http://localhost:8080/

---
Built on 2025-08-10 04:15:37

<!---
Melsonraven/Melsonraven is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
