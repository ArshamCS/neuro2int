# neuro2int personal website

A simple, responsive personal website built with plain HTML, CSS, and JavaScript.

## Why you don't see it on GitHub Pages yet

Your repository needs one of these to publish:

1. **GitHub Pages Source** enabled in repository settings, or
2. A **GitHub Actions deployment workflow** that publishes the site.

This repo now includes a Pages workflow at `.github/workflows/deploy-pages.yml`.

## One-time GitHub setup

1. Go to **Repository → Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push to `main` (or re-run the workflow from the Actions tab).

After deployment, your site URL will be shown on the Pages settings screen and in the workflow logs.

## Run locally

```bash
python3 -m http.server 4173
```

Open <http://localhost:4173>.

## Customize

- Update text content in `index.html`
- Adjust colors and layout in `styles.css`
- Add interactivity in `script.js`
