# My Wife Achal Saini 💕 — Happy Girlfriend Day 💌

A romantic, animated 3D web experience built with love for Achal Saini. Featuring 3D interactive particle effects, love letter envelope, personalized gallery of 13 moments, and background romantic music.

## What's inside
- **Hero** — full-screen intro with real-time 3D floating hearts field built with Three.js (particles react to mouse/touch).
- **Romantic Background Song** — automatic playback with interaction fallback and floating music toggle.
- **Envelope** — 3D CSS envelope you click to open, revealing a personal love letter.
- **Stats** — "days together" live counter.
- **Flip Cards** — 10 reasons why I love you with 3D flip animation.
- **Frames Worth Keeping** — 3D Coverflow gallery containing 13 real moments, matching captions, navigation dots, and full-screen lightbox viewer.
- **Closing** — pulsing heartbeat animation and "Send Love" floating heart burst.

## Deploy on Vercel 🚀
1. Go to [vercel.com](https://vercel.com) and log in with your GitHub account.
2. Click **"Add New..."** → **"Project"**.
3. Import **`amansainimomo0000-code/My_wify_Achal_saini`**.
4. Leave Framework Preset as **Other** (Root directory `./`).
5. Click **"Deploy"** — your live romantic website will be live with free SSL in seconds!

## How to run locally
1. Unzip the folder.
2. Open the folder in VS Code.
3. Install the **Live Server** extension (if you don't have it), right-click `index.html` → **Open with Live Server**.
   - Or just double-click `index.html` to open it in your browser directly.
4. Click the **✎ Edit** button (top right) to set her name, your signature, and your "together since" date. It saves in the browser automatically.
5. Click **Full Screen** in the bottom-right corner for fullscreen mode. Press **Esc** to exit.

## Customizing
- **Name / signature / date**: use the ✎ Edit panel in the browser — no code needed.
- **The letter text**: edit the `<div class="letter">` paragraph content in `index.html` (around line 45).
- **The 10 reasons**: edit the `reasons` array near the top of `script.js`.
- **Gallery images**: six local portrait illustrations are already included in `assets/` and loaded from the `portraits` array inside `initCarousel()` in `script.js`.
- **Use your own photos later**: add your files to `assets/`, then replace any `src` value such as `assets/cute-girl-1.svg` with `assets/photo1.jpg`. Keep portrait photos around a 4:5 ratio for the cleanest result.
- **Colors**: all colors are CSS variables at the top of `style.css` under `:root` — change `--rose`, `--gold`, `--bg-deep`, etc.

## Notes
- Uses three.js r128 via CDN (`cdnjs.cloudflare.com`) and Google Fonts (Playfair Display + Quicksand) — an internet connection is needed the first time these load.
- Fully responsive, works on mobile.
- Respects `prefers-reduced-motion`.

Made for Girlfriend Day, Aug 1. 🤎
## Full-view gallery

- Click the active center portrait (or press Enter/Space) to open it in a full-screen viewer.
- Press **Esc**, click the **×** button, or click the dark backdrop to close it.
- Use the arrow keys/buttons or swipe on mobile to change photos while the viewer is open.

