# My Personal Website

[Live preview](http://kodymoodley.github.io)

This repository contains a static personal website served from the repository root. There is no build step required — the site is plain HTML/CSS/ assets.

Local preview (quick):

```bash
# from the repo root
python3 -m http.server 8000
# open http://localhost:8000
```

Publish to GitHub Pages (automatic):

Because this repository is named `kodymoodley.github.io`, GitHub Pages will publish the repository root automatically when you push. Example:

```bash
git add .
git commit -m "Update site"
git push origin master
# then visit https://kodymoodley.github.io after GitHub finishes building
```

Notes:
- I added a `.nojekyll` file so GitHub Pages will serve files as-is (no Jekyll processing). If you later want to use the `jekyll-theme-slate` or other Jekyll features, remove the `.nojekyll` file and add a `Gemfile` to use Jekyll locally.
- If you need help adding a blog, templates, or a CI workflow, I can add a minimal Jekyll setup or a GitHub Actions deploy workflow on request.