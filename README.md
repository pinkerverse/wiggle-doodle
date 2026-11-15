# Wiggle Doodle V2

An iPad-friendly animated drawing PWA with 7 brushes, gentle wiggle intensity, kawaii and soft bleed effects, Apple Pencil/touch/mouse support, Instagram 9:16 canvas, and 4-second looping MP4 export (browser support varies).

## Live site

After enabling GitHub Pages using the main branch and root folder, open https://pinkerverse.github.io/wiggle-doodle/.

## Setup

The site is static: no build, dependencies or server are necessary. Open the GitHub repository's **Settings → Pages**, select **Deploy from a branch**, **main**, and **/(root)**, then **Save**.

For iPad installation, open the HTTPS Pages website in Safari and use **Share → Add to Home Screen**.

## Notes

MP4 uses browser H.264 support and may be unavailable on some devices; test video export on the target iPad. The drawing and service-worker offline cache do not require a backend. All drawing data stays in the browser.
