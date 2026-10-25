# Alkhwarizmi AI Academy website

Single-page static site. `index.html` is the page; `media/` holds the WebP images
and the share card, `fonts/` the self-hosted Aileron brand font.

It is published with GitHub Pages from the `gh-pages` branch at
https://sheedosa.github.io/Alkhwarizmi-website-LATEST/

Every push to the default branch runs `.github/workflows/pages.yml`, which copies
`index.html`, `media/` and `fonts/` to `gh-pages` so the live site updates automatically.
