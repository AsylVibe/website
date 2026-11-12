# Asylkhan Mamyrbek — Creative Developer Portfolio

A single-page portfolio built with semantic HTML, CSS, and vanilla JavaScript. It follows a dark editorial / futuristic chrome direction inspired by the supplied reference.

## Run locally

Serve the folder over HTTP because the sculpture loads Three.js as an ES module:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Publish with GitHub Pages

The GitHub Actions workflow deploys the site on every push to `main`. In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**. After the first successful deployment, the site will be available at `https://asylvibe.github.io/website/`.

## Editing

- Copy and section structure: `index.html`
- Layout, typography, color, responsive rules: `style.css`
- Editable project data, interactions, and Three.js sculpture: `script.js`

Project links and contact details intentionally use placeholders until real information is supplied.
