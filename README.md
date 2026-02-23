# PepePe — Single-file Static Site

This repository contains a small single-page static website ready for publishing to GitHub Pages.

Files created:

- index.html
- styles.css
- .nojekyll

Quick publish steps (from repo root):

1. Initialize git and push to GitHub:

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin git@github.com:your-username/your-repo.git
git push -u origin main
```

2. Enable GitHub Pages in repository settings using the `main` branch (or use `gh-pages` branch if you prefer).

Alternative: publish to `gh-pages` branch:

```bash
git checkout -b gh-pages
git push -u origin gh-pages
```

3. Optional: add a `CNAME` file at the repo root with your custom domain.

Notes:
- Update the contact details in `index.html`.
- `.nojekyll` is included to prevent Jekyll processing on GitHub Pages.
