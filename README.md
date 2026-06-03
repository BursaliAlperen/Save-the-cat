# Save The Cat — AAA Physics Edition

A polished single-file HTML5 puzzle game where the player draws live physics shields to save the cat from bees, traps, projectiles, moving hazards, and themed stage mechanics.

## What changed from the prompts

- Real-time drawing feedback: every stroke appears while the user is drawing, not only after release.
- Smarter physics puzzle flow: stages now include gravity, friction, collisions, moving hazards, projectiles, trap interactions, and survival timing.
- Anti-cheese draw rules: drawing directly on or tightly around the cat/hive triggers a red warning and rejects the unsafe cage.
- AAA-style stage briefing: each level opens with a quick “3-second plan” popup explaining the theme, traps, and expected player strategy.
- Audio routing: `assets/loading.mp3` is reserved for loading, while `assets/background.mp3` is used as the background loop.

## Run locally

Open `index.html` in a browser, or serve the repository directory with a local static server.

## Design notes

- The game is intentionally mobile-first with a tall 9:16 canvas.
- Every stage asks for a small tactical idea rather than blind scribbling.
- Traps are introduced with readable tutorial copy before play starts.
- Drawing near protected entities is blocked to keep the puzzle fair.
- Survival starts only after the player presses the bee release button.
- The handmade stage pack now covers multiple unique trap combinations before procedural levels continue.
- Loading and background music are separated for clearer presentation polish.
