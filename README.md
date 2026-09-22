# Fogged Glass

A webcam mirror you can breathe on. Blow near your mic to fog it up, pinch your fingers to wipe it clean.

Live: https://lahersoni.github.io/fogged-glass/

## How to use it

- Blow on your screen (or near the mic) to fog up the glass
- Pinch your thumb and index finger together to wipe the fog away
- Hold both hands in an L shape for about a second and a half to take a photo
- Photos show up at the bottom, hover and click save to download them
- Undo/clear buttons are in the top right

## How it's built

Just HTML, CSS and JS, no frameworks. Uses MediaPipe Hands for tracking your fingers and the Web Audio API to detect breathing through the mic.

## Running it yourself

Can't just open the file directly since camera/mic need a secure origin. Run a local server instead: python3 -m http.server 8000, then open localhost:8000 in Chrome.

## Notes

Works best in Chrome on desktop. Needs a webcam and mic obviously. Deployed with GitHub Pages.
