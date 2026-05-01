# Kontoh TreeMap

This repository is configured to deploy `index.html` to GitHub Pages using a GitHub Actions workflow.

## Why you were seeing 404

A GitHub Pages `404 File not found` for a root URL usually means one of these:

1. Pages wasn't enabled for the repository.
2. The selected source branch/folder didn't contain `index.html`.
3. The site was opened before deployment finished.

## Deployment setup in this repo

- Workflow file: `.github/workflows/deploy-pages.yml`
- Root page file: `index.html`
- Jekyll bypass marker: `.nojekyll`

## How to publish

1. Push this branch to GitHub.
2. In GitHub: **Settings → Pages**
   - Source: **GitHub Actions**.
3. Wait for the **Deploy static site to GitHub Pages** workflow to complete.
4. Open:
   - `https://<your-username>.github.io/Kontoh_TreeMap/` (project site), or
   - `https://<your-username>.github.io/` (if this repo is named `<your-username>.github.io`).

> Note: GitHub Pages URLs are case-sensitive for repository names and paths.
