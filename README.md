# Myotrek

Interactive 3D explorer of joints and the muscles that move them, for patients and physiotherapy learners.

Pages:

- `index.html`: landing page
- `body.html`: the whole skeleton; tap a joint to open it
- `elbow.html`, `knee.html`, `shoulder.html`: in depth (exercises, every muscle working, Simple and Clinical levels)
- `joint.html?j=…`: first drafts of the wrist, hip, ankle, neck and lower back
- `exercises.html`: the exercise library (arms: biceps, triceps and compound exercises)
- `exercise.html?e=…`: one exercise in 3D, with how-to steps and sets and reps

Add `?side=left` to a joint page for the left side.

## Run it

Each page is a single HTML file with no build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Three.js 0.160 loads from the jsDelivr CDN, so you need an internet connection.

## Content

Clinical content is a draft and is being reviewed by a physiotherapist.

## Roadmap

- More of the exercise library: shoulders, legs (squats, leg raises, Nordics) and trunk
- In-depth wrist, hip, ankle, neck and lower back
- Quiz mode
