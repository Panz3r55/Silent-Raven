# Silent Raven Agency website

One-page site for Silent Raven Agency, a studio that builds custom websites for local businesses. AI drafts them fast. People make them yours.

Live at https://silent-raven.vercel.app

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site: markup, styles and scripts in one file |
| `assets/hero-scrub.mp4` | The hero video. It plays forward and backward as the visitor scrolls |
| `assets/hero-poster.jpg` | First frame of the video, shown while it loads |
| `assets/hero-ending.jpg` | The sharp final frame. Also used in the Proof section and for link previews |
| `assets/hero-mobile.jpg` | The tall still image phones get instead of the video |
| `assets/raven-mask.png` | The raven's outline. It makes the big wordmark turn from solid to outlined where it crosses the bird |

No build step, no framework. Open `index.html` through any static host. Opening the file directly from disk shows the still-image hero, because browsers block the video loader on `file://` addresses.

## Design

- **Colors:** canvas `#0A1118`, panel `#111B23`, text `#ECE8DD`, secondary text `#A3B3B8`, accent baby blue `#8FD0F2`. All are CSS variables at the top of `index.html`.
- **Fonts (Google Fonts):** Lexend 800 (the SILENT RAVEN wordmark), Archivo at expanded width (headlines), Instrument Sans (body), JetBrains Mono (small labels).
- **Hero:** a full-width SILENT RAVEN wordmark over a scroll-driven video of the raven in fog. The letters are solid over the fog and outlined over the bird. Phones, portrait tablets and visitors who prefer reduced motion get a designed still image and never download the video.
- **Imagery:** the raven is a real photo. The fog and the motion were made with AI and directed by people. The footer says so.

## Page sections

1. Hero: the wordmark, four short lines in the lower left, then the headline and the call to action
2. The usual story: three common complaints, each answered
3. How it works
4. Services
5. Process, with a press-and-hold button that clears the fog off the five steps
6. Proof
7. Questions
8. Contact form

## Still to do

- **Connect the contact form to an inbox.** It is in preview mode and sends nothing. The thank-you message says so.
- Add client projects and reviews to the Proof section as they launch.
- If the site moves to a custom domain, update the two `og:` URLs marked `DEPLOY STEP` in `index.html`.

The previous version of the site (the wordmark hero with the feather animation) is in this repository's history.
