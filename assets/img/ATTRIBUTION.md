# website/assets/img Attribution

Images used on the tester landing page (`website/index.html`). Both are
freely redistributable — unlike the Czepeku/TabletopAudio personal-use
library in the top-level `assets/`, nothing here needs to stay out of git.

| File | Source | License |
|---|---|---|
| `scene-misty-forest-path.jpg` | `forest_fog.jpg` from the app's own CC0/Pexels starter pack (`assets/images/Starter Pack - CC0-CC-BY/`), photo by Francesco Ungaro | Pexels License — free for commercial use, no attribution required |
| `tactical-map-manor-hall.png` | `Sample2.png` from Kenney's "Roguelike/RPG pack" (kenney.nl/assets/roguelike-rpg-pack) | CC0 1.0 Universal — public domain, no attribution required |
| `genesisdm-logo.png` / `genesisdm-logo.pdf` | Original GenesisDM brand mark (open book + crescent moon) | First-party — no license needed |

`tactical-map-manor-hall.png` is website-only for now; it is not part of
the app's shipped starter pack (see `assets/STARTER_PACK_ATTRIBUTION.md`,
which notes no CC0 tactical maps were available when that pack was built).

`genesisdm-logo.png`/`.pdf` are the master source files for the site's
logo; the header/favicon mark in `index.html`/`faq.html` is a
hand-vectorized inline `<svg>` rendition of this same mark, kept inline
so the page stays self-contained with no extra image request.
