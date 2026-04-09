# Jeo Portfolio

Single-page portfolio site built with plain **HTML, CSS, and JavaScript**.

## Live site

- https://jeo-portfolio-08.vercel.app/

## Tech stack

- HTML5
- CSS3 (custom properties, glassmorphism, responsive layouts)
- Vanilla JavaScript (UI state, clock widget, reveal animations, canvas background)

## Local development

Because this project is static, you can run it directly or serve it locally:

```bash
# Option 1: open directly
open index.html

# Option 2: serve with Python
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Current UX behavior highlights

- Desktop floating sidebar + mobile drawer navigation.
- Day/Night mode with localStorage persistence.
- Morphing clock widget (digital, analog, ring).
- Animated background layers with reduced-motion awareness.
- Mobile first-view zoom-out effect for a better initial overview.

## Repository structure

```text
.
├── index.html
├── profile-photo.png
└── README.md
```
