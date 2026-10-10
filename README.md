# Valdez static website

## Quick start
1. Open `index.html` and find the `SITE` configuration near the bottom.
2. Replace blank URLs with your actual song, YouTube video, and social links.
3. For real cover artwork, put an image in `assets/` and set `coverArt: 'assets/im-gone-cover.webp'` (adjust to its real filename).
4. Add a show in `nextShow` only if you have a confirmed upcoming event.
5. Commit `index.html` and `assets/hero.webp` to the root of your GitHub repository.
6. On Sevalla, deploy your existing static site from that repository. Build command: none (plain HTML). Publish/output directory: repository root (often `.`), if requested by your Sevalla configuration.
7. Verify the live page on mobile and desktop. Confirm links, image loading, and domain/HTTPS.

No dependencies, no build step. The hero photo is from the supplied user image.

IMPORTANT: Add your actual cover art at assets/DarkCountryThumb.jpg before deploying. The image was not included in the supplied files.
