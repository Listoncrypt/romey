# Romey portfolio

A responsive single-page portfolio for Romey, a Discord Moderator and Regional Ambassador. The only social and contact destination is X: `https://x.com/romeydontlie`.

## Preview

Open `index.html` in a browser. The two display fonts load from Google Fonts; the page falls back to system fonts if they are unavailable.

## Deploy to Vercel

This is a static HTML, CSS, and JavaScript site. In Vercel, create a project from this folder and choose the **Other** framework preset. Leave the Build Command blank and set the Output Directory to `.`. `index.html` is at the project root, so no build step or framework dependencies are needed. Vercel serves static HTML/CSS/JS without a build command. [Vercel build configuration](https://vercel.com/docs/builds).

The banner is a cleaned copy of the image supplied for this site; the source image was not modified.

## Banner resolution

The page uses `assets/romey-banner-4k.jpg`, a 3840 × 1280, 4K-width export that preserves the supplied image's 3:1 shape. The source was 1500 × 500, so the export is resampled and edge-sharpened; it has more display pixels but cannot recover detail that was not present in the source.

On narrow phone screens, the hero uses a portrait crop focused on the character so the image remains visible in the tall layout. The heading and role copy sit below it on the orange field for clear contrast.
