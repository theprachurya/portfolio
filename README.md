# Prachurya's Portfolio

A responsive, static portfolio for selected software projects, GitHub activity, and contact links. PageTurn is the featured project. Motion includes a staggered hero entrance, scroll reveals, and subtle hover feedback, with reduced-motion support. The GitHub widget reads public profile and repository stats from the GitHub REST API and caches them in the browser for one hour.

## Run locally

Open `index.html` in a browser, or serve the repository root with any static file server:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Publish

The repository deploys to GitHub Pages from `master` with the workflow in `.github/workflows/static.yml`. It serves the repository root as-is; no package installation or build step is required. Project links and copy live directly in `index.html`.
