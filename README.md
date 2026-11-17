# Until I Wake / Kým sa zobudím

A short narrative puzzle game (10 stages, 15-20 minutes) about Elena, who has been in a coma
for eleven days. Her body sleeps; her mind keeps walking home - cradle, kindergarten, first
love, wedding, children, the road back. In every memory there is one thing that does not
belong. Find it, and the dream opens into the next stage.

Play: https://najxo.itch.io/until-i-wake

## Game Off 2026 - theme: SHIFT

Every stage is a *shift*: the memory shifts to another period of her life, the picture shifts
around a single object that does not belong to it, and the story shifts from coma back toward
waking. The last scene is the shift the whole game is built around - the road, the car, and the
one moment that has to change for her to come back. English by default, Slovak one tap away.

## Controls

- Click / tap the object that does not belong in the picture.
- Arrow keys or Tab move between highlights, Enter selects.
- **EN / SK** switches the language, **FS** (square icon) toggles fullscreen.
- No timer, no fail state.

## Where the game lives

- `beta/` - current build (`index.html` + `assets/`), served at
  https://najxosk.github.io/until-i-wake/beta/index.html and packaged for itch.io
- `play/`, `preview/` - earlier iterations, kept for history

## AI disclosure

- **AI art** - all ten scene paintings, the cover and the end illustration were generated with
  image models from hand-written prompts and hand-picked between variations.
- **AI assistance for code and text** - the HTML/CSS/JS and the English/Slovak story text were
  written with an AI assistant.
- **Hand-made** - concept, story outline, characters, names, all creative decisions, puzzle
  placement choices, the sound design (synthesised live in the browser, no samples) and
  playtesting.

## Tech

Single HTML file, no build step, no dependencies. All audio is synthesised in the browser.
