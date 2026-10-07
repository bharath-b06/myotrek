# Myotrek

Interactive 3D explorer of joints and the muscles that move them, for patients and physiotherapy learners.

**v1: the elbow.** Bend and straighten the arm and watch the muscles shorten, lengthen and bulge. Muscles are coloured by contraction type (concentric, eccentric, isometric). You can switch forearm position (palm up, thumb up, palm down) and load (weight or band), and each muscle has an info card with Patient and Learner levels.

## Run it

It's a single page with no build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Three.js 0.160 loads from the jsDelivr CDN, so you need an internet connection.

## Content

Clinical content is a draft and is being reviewed by a physiotherapist.

## Roadmap

- Pronation and supination (radioulnar joints), plus pronator teres
- Quiz mode
- Dark mode polish
- More joints: shoulder, wrist, full body
