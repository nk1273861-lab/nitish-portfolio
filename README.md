# Nitish Kumar — Creative Full Stack Developer Portfolio

A cinematic, interactive single-page portfolio built entirely in HTML, CSS and vanilla JavaScript — no frameworks, no build step.

## About

Nitish Kumar is a Diploma in Computer Science Engineering graduate (completed 2026, First Division) and a Full Stack Web Development fresher, focused on frontend and backend web development.

## Tech stack

- HTML5, CSS3, JavaScript, DOM
- Bootstrap concepts, Responsive Web Design
- PHP, MySQL
- Git, GitHub
- AI-assisted development / prompt engineering

## Features

- Cinematic cosmic particle hero that transforms into the developer's name and title
- Click / tap to trigger the transformation, plus a "reform the matter" reset
- Custom cursor and subtle parallax starfield on desktop
- Glassmorphism UI system throughout
- 3D-tilt project cards (disabled on touch devices)
- Featured project panel — Sunami Water Park
- Live JavaScript booking calculator (frontend demo only, no real payments)
- Digital tech skill constellation rendered on canvas
- Horizontal scrolling tools strip
- Certification training timeline and education panel
- Magnetic button, glass mode toggle, accessible accordion
- Scroll-reveal animations
- Full `prefers-reduced-motion` support
- Fully responsive from 320px to 1920px, keyboard accessible, semantic HTML

## Project structure

```
nitish-kumar-portfolio/
├── index.html          # everything — markup, styles and scripts
├── README.md
├── .gitignore
└── assets/
    └── images/
        ├── nitish.png          # original portrait, used in the About section
        └── nitish-cutout.png    # background-removed / feathered-glow cutout used in the hero
```

## Run locally

No build step is required. Just open `index.html` directly in a browser, or serve the folder with any static file server:

```bash
# Python
python3 -m http.server 8080

# Node
npx serve .
```

Then visit `http://localhost:8080`.

## Deploy to GitHub

1. Create a new repository on GitHub.
2. From inside the `nitish-kumar-portfolio` folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin YOUR_GITHUB_REPO_URL
   git push -u origin main
   ```

## Deploy to GitHub Pages

1. Push the project to GitHub (see above).
2. In the repository, go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — GitHub will publish the site at `https://YOUR_USERNAME.github.io/REPO_NAME/`.

## Deploy to Render (Static Site)

1. Push the project to GitHub.
2. In Render, choose **New → Static Site** and connect the repository.
3. Set:
   - **Build command:** (leave empty)
   - **Publish directory:** `.`
4. Deploy — Render serves `index.html` directly, no backend or Node.js setup required.

## Notes

- Contact links (`YOUR_EMAIL`, `YOUR_GITHUB_URL`, `YOUR_LINKEDIN_URL`, `YOUR_RESUME_URL`) are placeholders — replace them in `index.html` with real links before publishing.
- No API keys, credentials or secrets are used anywhere in this project.
- All project descriptions are concept/academic work; no production metrics or clients are claimed.
