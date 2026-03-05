# Tall Grass Encounter

A single-page Pokémon-themed interactive site built with HTML and CSS only — no JavaScript.

Three tall grass patches sit side by side on a Pokémon route. Hover to make the grass rustle. Click to commit to a patch and reveal what's hiding inside.

## What's Inside

| Patch | Outcome |
|-------|---------|
| Left | ✨ Shiny Mew — ultra rare! |
| Middle | Magikarp — it splashed uselessly. |
| Right | No Entry — path is blocked. |

## Features

- Pure CSS interactions (checkbox/radio hack, `:has()` for reset visibility)
- Grass rustle animation on hover (`@keyframes`)
- Neo-brutalist design: bold black borders, offset drop shadows, flat block colors
- Fully responsive: desktop, tablet, mobile (3+ media queries)
- All layout in viewport units (`vw`, `vh`, `vmin`)
- CSS selector demo: `:hover`, `:active`, `:focus`, `:checked`, `~`, `+`, `>`
- Reset button clears selection via native `<button type="reset">`
- No JavaScript

## How to Run Locally

Open `index.html` in any modern browser — no build step or server needed.

```bash
open index.html
```

## File Structure

```
AotW-S1-A2/
├── index.html          ← single page, all CSS embedded
├── img/
│   ├── bg.png          ← Pokémon route background scene
│   ├── grass.png       ← tall grass tile (reused 3×)
│   ├── magikarp.png    ← Magikarp official artwork (PokeAPI)
│   ├── mew-shiny.png   ← Shiny Mew official artwork (PokeAPI)
│   └── no-entry.png    ← No Entry sign illustration
└── README.md
```

## Credits

- Pokémon artwork sourced from [PokeAPI](https://pokeapi.co) official artwork sprites
- Pokémon and all related names are trademarks of Nintendo / Game Freak
- Built for Art of the Web — Season 1, Assignment 2
