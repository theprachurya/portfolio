# Prachurya's Portfolio

A responsive, static portfolio site that presents selected software projects, engineering tools, background, and contact links.

## Run locally

Open `index.html` in a browser, or serve the repository root with any static file server:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Publish

The repository deploys to GitHub Pages from `master` with the workflow in `.github/workflows/static.yml`. It serves the repository root as-is; no package installation or build step is required. Update project cards and their matching entries in the `PROJECTS` object in `index.html` together so the search, filters, and detail dialog stay in sync.
