# nathanaelhub.github.io

My personal site — hand-written HTML/CSS/JS, no framework, no build step.
Live at **https://nathanaelhub.github.io/**.

## Structure

```
index.html              # single-page portfolio (nav, projects, education, about)
assets/
├── css/styles.css      # all styling
├── scripts/scripts.js  # typewriter intro + project filter buttons
├── img/                # project icons (drawn with DALL·E 3) + photos
└── projects/           # PDFs and write-ups the project cards link to
```

## Local preview

No tooling needed:

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

Pushing to `main` deploys via GitHub Pages.
