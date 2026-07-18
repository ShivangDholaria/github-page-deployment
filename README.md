# GitHub Page Deployment

A minimal static site used to demonstrate deploying to GitHub Pages via GitHub Actions.

## Contents

- [index.html](index.html) — single-page "Hello, GitHub Actions!" site

## Deployment

This site is intended to be published with GitHub Pages, either by:

- Serving directly from the `main` branch (Settings → Pages → Deploy from a branch), or
- Using a GitHub Actions workflow (e.g. `actions/upload-pages-artifact` + `actions/deploy-pages`) to build and publish on push.

## Local preview

Open [index.html](index.html) directly in a browser, or serve it locally:

```bash
npx serve .
```

Project Link: https://roadmap.sh/projects/github-actions-deployment-workflow