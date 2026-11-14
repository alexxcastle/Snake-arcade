# Snake Arcade

Pixel-art Snake built with vanilla HTML, CSS and Canvas. Keyboard (arrows/WASD), swipe and touch D-pad controls; score and best score stored locally.

## Deploy on Vercel
1. Import this repository into Vercel and deploy as a static site (no build command).
2. Replace `YOUR-VERCEL-DOMAIN` in `index.html` with the deployed domain in the `twitter:player` and `twitter:image` metadata.
3. Redeploy.

## X Player Card note
The `twitter:card=player` metadata is experimental for interactive games. X controls whether it renders and may not support arbitrary game embeds in every client. Test the published URL on the intended X clients.

Files: `index.html` (landing + card metadata), `game.html` (game), `poster.svg` (preview), `vercel.json` (frame policy).