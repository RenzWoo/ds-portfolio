# Data Science Portfolio

Personal Data Science portfolio built with [Jupyter Book](https://jupyterbook.org) and hosted on GitHub Pages.

**Live site:** https://RenzWoo.github.io/ds-portfolio/

## Structure

```text
ds-portfolio/
├── _config.yml                      # site title, author, repo link
├── _toc.yml                         # navigation (projects grouped by theme)
├── intro.md                         # homepage
├── projects/
│   ├── smart-trip-cdo.ipynb         # static RAG itinerary generator
│   ├── market-direction-ml.ipynb    # forex direction prediction (tabular ML)
│   ├── kaggle-dataset-finder.ipynb  # LLM + embeddings dataset discovery
│   ├── coffee-bootstrap.ipynb       # bootstrap CI study (R)
│   ├── visitor-tracker.ipynb        # FastAPI + SQLite pipeline
│   ├── diabetes-3d-map.ipynb        # 3D county choropleth (R)
│   └── volcanic-eruptions.ipynb     # eruptions EDA + infographic (R)
├── images/                          # posters, infographics, profile photo
└── data/                            # small CSVs used by executable cells
```

Notebooks are shown as saved (`execute_notebooks: "off"`), so charts are embedded in each `.ipynb`.
To refresh a chart, re-run the notebook in Jupyter, save it, then rebuild.

## Build locally

```bash
pip install -U "jupyter-book<2" ghp-import matplotlib pandas
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
