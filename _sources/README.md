# Data Science Portfolio

Personal Data Science portfolio built with [Jupyter Book](https://jupyterbook.org) and hosted on GitHub Pages.

**Live site:** https://YOUR-USERNAME.github.io/ds-portfolio/

## Structure

```text
ds-portfolio/
├── _config.yml        # site title, author, repo link
├── _toc.yml           # page order / navigation
├── intro.md           # homepage
├── project1.ipynb     # project notebooks
├── project2.ipynb
└── images/            # profile photo, charts, thumbnails
```

## Build locally

```bash
pip install -U "jupyter-book<2" ghp-import
jupyter-book build .
```

Open `_build/html/index.html` in your browser.

## Publish

```bash
ghp-import -n -p -f _build/html
```

## Update workflow

```bash
jupyter-book build .
git add .
git commit -m "Update portfolio"
git push
ghp-import -n -p -f _build/html
```
