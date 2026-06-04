# Beating Heart — Pure CSS

A heart that beats, built with nothing but HTML and CSS. No images, no JavaScript, no dependencies — a single self-contained `index.html`.

**Live demo:** https://danielt69.github.io/Beating-heart-pure-css/

## How it works

The heart is two CSS pseudo-elements (`::before` and `::after`) — rounded rectangles rotated ±45° and joined at the base. A `@keyframes` animation scales it on a double-thump rhythm to mimic a real heartbeat, with a soft glow via `drop-shadow`. Motion is disabled automatically for users with `prefers-reduced-motion`.

## Run locally

Just open `index.html` in any browser. That's the whole project.
