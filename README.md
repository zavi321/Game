# Threadwalk

A browser-based prototype of an arrow-path tracing puzzle game — trace a continuous thread through a grid by following arrow directions from start to goal.

## How it works

- Each level generates a random Hamiltonian path across the grid (a single route that visits every cell exactly once).
- Arrows in each cell point toward the next cell in the path.
- Drag from the green start cell, following the arrows, to the coral goal cell.
- Three difficulty presets change the grid size: Easy (5×6), Medium (6×8), Hard (7×9).

## Run it

Just open `index.html` in any modern browser — no build step, no dependencies.

```
git clone <your-repo-url>
cd threadwalk
open index.html
```

## Roadmap

This is a web prototype meant to validate the core mechanic before porting to mobile. Planned next steps:

- [ ] Port grid + path-generation logic to Unity (C#)
- [ ] Touch input via Unity's Event System (OnPointerDown / OnDrag / OnPointerUp)
- [ ] Level seeding so specific layouts can be saved/replayed
- [ ] Hints, timer, and sound
- [ ] Android/iOS build

## Tech

Single-file HTML/CSS/JS. No frameworks, no build tools.

## License

MIT
