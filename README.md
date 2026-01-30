# LUU_BUCS.github.io

BUCS Dashboard GitHub Pages site served from `index.html`.

## Local preview (optional)
If you want to preview locally with Jekyll, you can use:

```bash
bundle init
bundle add github-pages
bundle exec jekyll serve --livereload
```

Then open: http://localhost:4000

## Deploy
Push to GitHub and enable **Pages** in the repo settings.
Choose either:
- **Deploy from a branch** → `main` (or `master`) and root `/`
- Or **GitHub Actions** if you prefer a workflow

Your site will be available at `https://<username>.github.io/<repo>/`.
