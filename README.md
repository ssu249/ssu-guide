# University platform (optimized)

Static site, GitHub Pages ready: upload this folder's contents to the repo root (or /docs) and enable Pages.

```
index.html            page markup (no inline CSS/JS)
css/style.min.css     all site styles (minified)
css/noscript.css      fallback styles when JavaScript is off
js/data.js            content/config/translations (deferred)
js/app.js             core logic, routing, rendering (deferred)
js/search.js          global search, loaded when idle / on first use
js/gallery.js         image-page renderers, loaded on first visit to those pages
assets/img/           all images (WebP; favicon is PNG), grouped by page
```
Notes: place/college photos are center-cropped to 16:10 (what the CSS displayed). Keep your originals if you ever change `object-fit`.
