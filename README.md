# Silent Raven Agency website

One-page website for Silent Raven Agency, a creative studio that uses AI to build custom websites faster and more affordably.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site: markup, styles and scripts in one file |
| `raven2.webp` | Raven silhouette, cut out on a transparent background |
| `wind.png` | Movement map for the feather animation: white areas move, black areas stay still (beak and eye) |

No build step. Open `index.html` in a browser, or serve the folder with any static host (Vercel, Netlify, GitHub Pages).

## Design

- **Colors:** stone `#C1BBAE`, paper `#EEE9DE`, ink `#17130D`, ink soft `#524B3D`, orange `#F15A24`, orange for text `#A8360C`, wordmark `#B04E2A`. All are CSS variables at the top of `index.html`.
- **Fonts (Google Fonts):** Archivo (headlines and wordmark, expanded width), Inter (body), JetBrains Mono (small uppercase labels).
- **Hero:** the "silent raven" wordmark is drawn twice. The solid copy sits behind the raven photo and the outlined copy sits in front of it, so the letters turn into outlines where they cross the bird.
- **Feather animation:** a small WebGL shader warps the raven image using `wind.png` as a mask, with gusts and a slow breathing motion. It pauses when the hero is off screen and is skipped for visitors who prefer reduced motion.

## Page sections

1. Hero: labels, wordmark, headline, supporting line
2. How it works: AI drafts, people decide, you launch sooner
3. Services
4. Process (five steps)
5. Work (placeholders)
6. Contact form

Also: a full-screen menu (Menu button) and an "Ask the Raven" button in the bottom-right corner, reserved for a future AI assistant.

## Still to do

- Replace the bracketed placeholders: portfolio projects and reply time
- Confirm the real email address (currently `hello@silentraven.agency`)
- Connect the contact form to an inbox (it currently shows a "not connected yet" message)
- Build the AI assistant behind "Ask the Raven"
