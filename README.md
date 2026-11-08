# Hue's Got Flow: The Coloring Odyssey

A hip-hop coloring book adventure game for the browser, phones and VR headsets, built with Three.js and WebXR.
Based on *Hue's Got Flow: A Hip-Hop Coloring Odyssey* by Darnell Clark, PenGame Publishing.

**Play:** https://mrimagemakers.github.io/HuesGotFlow/

## What's in the game
- 12 levels across New York and the Coloring Odyssey, with bosses in Levels 5, 8, 11 and 12 (the Eraser King)
- The Golden Pen: draw lines, squares, circles, spirals and X's to change the world
- Dimension Bounce between New York, the Odyssey and Ink Space
- Summonable sidekicks Brush and Dot, unlocked by side puzzles
- Hue levels 1–10 with gliding, flight and new specials
- 4 difficulty tiers, a ChromaFlow painter studio, and WebXR play on Meta Quest

## Hue's character model
Hue uses character model 00 from [Porch War](https://github.com/Mrimagemakers/PorchWar) (`models/rigged/character-00.glb`), reskinned in-game to match the flyer art: blue graffiti-print jacket over a red hoodie, red snapback, white shades, gold chains. Idle, walk and run animations are baked onto its Mixamo rig (`assets/hue-pw.json`).

## Running locally
Any static web server works, for example:

```
python3 -m http.server 8000
```

Then open http://localhost:8000. Three.js loads from the jsDelivr CDN. VR needs HTTPS (GitHub Pages provides it).

## Deploying
Pushing to `main` deploys automatically through the GitHub Actions workflow in `.github/workflows/pages.yml`.
In the repo settings, set **Pages → Source** to **GitHub Actions** once.

© PenGame Publishing, LLC. All artwork, story and characters belong to their owner.
