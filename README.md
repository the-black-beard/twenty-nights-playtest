# Twenty Nights Playtest Workshop

A separate static playtest site for Twenty Nights. This repository hosts design sketches and the existing controls/swarm harness; it does not change the main game.

- `index.html`: playtest home page and mobile QR link.
- `workshop/index.html`: offline, self-contained maze workshop with guided comparisons, editable maze and local note export; the canvas fits narrow grid columns.
- `controls/index.html`: original control and swarm logic; the toolbar wraps on narrow screens.
- `assets/`: static maze diagram and locally generated QR code.

Serve the root on GitHub Pages from `main` with `.nojekyll`. Individual test HTML files can also be opened offline. No build, application server, third-party runtime libraries or application analytics are used. Notes and measurements remain in the visitor's tab until copied/downloaded; these pages do not submit them.

The sketches are candidates for play and discussion. Matching structural measures and headless checks do not establish equal difficulty, touch quality or human acceptance. Final Nether layer design and monster counts remain open.
