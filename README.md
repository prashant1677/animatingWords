# animatingWords

A lightweight Three.js (r71) demo that renders an animated 3D “word logo” made of many icon/character particles.

## What it does
- Creates a large particle field in WebGL.
- Uses CreateJS to generate a text texture atlas.
- Uses TweenMax timelines for smooth choreography (camera motion + logo remap).
- Adds a timed sequence so the logo continuously re-forms.

## Demo
Open `index.html` in a browser.

## Libraries
- Three.js r71
- TweenMax 1.17
- CreateJS 2015
- WebFont.js

## Notes
- The animation relies on external font/texture URLs. If those requests are blocked, you may see a blank scene.
- `script.js` contains the initialization + rendering logic.


