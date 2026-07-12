# Sriraksha Murali - Portfolio

An interactive solar-system portfolio. Each planet is a section: Work, Experiments, Why me, Contact. Project cards open case studies in a slide-in panel.

## Structure

- `index.html` - entry point, redirects to the main design
- `Solar System Home.dc.html` - the portfolio homepage (main)
- `Solar System Home v1 (orbit).dc.html` - alternate orbit layout
- `Voice_Orb_v3.dc.html` - Voice AI assistant concept (linked from Experiments)
- `uploads/` - case study pages, shared stylesheet, and images
- `assets/` - planet artwork
- `support.js`, `ios-frame.jsx`, `image-slot.js` - design runtime and components

## Run locally

Any static server works:

```
python3 -m http.server
```

Then open http://localhost:8000

Opening the HTML files directly from disk also works for the homepage; the Voice Orb page needs to be served or online (it compiles its iPhone frame with CDN-loaded Babel/React).

## Deploy to GitHub Pages

1. Push this folder to a repository
2. Settings > Pages > Deploy from branch > `main`, root folder
3. The site serves at `https://<user>.github.io/<repo>/`
