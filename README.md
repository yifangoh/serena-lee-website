# serena-lee-website

One-page portfolio site for Serena Lee, a freelance wedding and portrait photographer. Plain HTML and CSS, no build step. Dark theme.

## Files

- `index.html` is the whole site (hero, portfolio grid, about, contact).
- `photo-01.jpg` is the first portfolio image. The other five slots are placeholders.
- `vercel.json` sets static hosting, security headers and image caching.

## Run locally

```
npm run dev
```

## Deploy on Vercel

1. Import this repo at https://vercel.com/new.
2. Leave the framework preset as "Other". There is no build command and the output directory is the repo root.
3. Deploy. Every push to `main` redeploys.

## Before going live

- Replace `hello@serenalee.com` in `index.html` with Serena's real address.
- Rewrite the about text in her own words.
- Swap the placeholder blocks for her photos: replace each `<div class="ph">` with `<img class="ph" src="your-photo.jpg" alt="Describe the photo">`.
- `photo-01.jpg` appears to be an iStock stock image. Replace it with Serena's own work or confirm the license.
