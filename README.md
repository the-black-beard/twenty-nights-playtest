# Twenty Nights Playtest Workshop

A separate static playtest site for Twenty Nights. This repository hosts design sketches and the existing controls/swarm harness; it does not change the main game.

- `studio/index.html`: a complete three-relic escape mission, distinct monster personalities, adjustable rules, controlled A/B comparisons, optional local drafts and note export. Preserves the authored Nether 1 and adds an optional reflected view; all rules are test proposals.
- `index.html`: playtest home page and mobile QR link.
- `monsters/index.html`: Nether 1, with clever, delayed-notice and wrong-turn monster candidates. This comparison does not introduce a retry difficulty ramp.
- `workshop/index.html`: offline, self-contained maze workshop with guided comparisons, editable maze and local note export; the canvas fits narrow grid columns.
- `controls/index.html`: original control and swarm logic; the toolbar wraps on narrow screens.
- `assets/`: static maze diagram and locally generated QR code.

Serve the root on GitHub Pages from `main` with `.nojekyll`. Individual test HTML files can also be opened offline. No build, application server, third-party runtime libraries or application analytics are used. Notes and measurements remain in the visitor's tab until copied/downloaded, or explicitly saved to this device using the studio's local draft button; these pages do not submit them.

The sketches are candidates for play and discussion. Matching structural measures and headless checks do not establish equal difficulty, touch quality or human acceptance. Final Nether layer design and monster counts remain open.

The studio uses a new movement engine and a return-home objective. Its results are not directly comparable with the earlier 45-second sketches. Relics persist through catches; winning does not mean an uncaught run. A/B preserves the recorded maze, goals, seed and ramp stage. Presets and three-life rules remain choices for the designer, not accepted game specifications.
