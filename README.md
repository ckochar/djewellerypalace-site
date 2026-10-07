# D Jewellery Palace website

Static site: `index.html` + `img/` + `video/`. No build step.

## Put it live (free, ~2 minutes)
1. Go to https://vercel.com/new and sign in.
2. Drag this whole folder (unzipped) onto the page and click Deploy.
   (Alternative: https://app.netlify.com/drop — drag the folder, done.)
3. Later, connect your domain in the project's Settings > Domains.

## Update details
Phone, WhatsApp, hours, addresses and Instagram are in one block near the
top of `index.html` (search for `const SITE`). Change them there only.

## Swap or add photos
Put the new photo in `img/`, then in `index.html` find the gallery
(`class="gallery"`) and change the `src` and caption of any tile.
Keep photos around 900px wide so the site stays fast.
