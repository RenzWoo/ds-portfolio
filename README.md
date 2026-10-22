# Data Science Portfolio

Personal data science portfolio by Renzo Alasan, built with [MyST Markdown](https://mystmd.org) and deployed to GitHub Pages.

**Live site:** https://renzwoo.github.io/ds-portfolio/

## Structure

```text
ds-portfolio/
├── myst.yml                  # site title, navigation, theme options
├── intro.md                  # homepage (hero, project cards, skills, about)
├── assets/
│   ├── custom.css            # GitHub-style dark theme
│   └── favicon.svg
├── projects/                 # one notebook per case study, shown as saved
│   ├── smart-trip-cdo.ipynb
│   ├── market-direction-ml.ipynb
│   ├── kaggle-dataset-finder.ipynb
│   ├── stock-candles-classification.ipynb
│   ├── coffee-bootstrap.ipynb
│   ├── visitor-tracker.ipynb
│   ├── diabetes-3d-map.ipynb
│   └── volcanic-eruptions.ipynb
├── labs/                     # laboratory tasks 1 to 6 (tasks 3 and 4 share one notebook)
│   ├── lab-task-1.ipynb
│   ├── lab-task-2.ipynb
│   ├── lab-tasks-3-4.ipynb
│   ├── lab-task-5.ipynb
│   └── lab-task-6.ipynb
├── images/                   # posters, infographics, avatar
├── data/                     # small CSVs used by notebook cells
└── .github/workflows/deploy.yml
```

Notebooks are rendered with the outputs saved inside them; the build does not re-run any code.
To refresh a chart, re-run the notebook in Jupyter, save it, and push.

## Preview locally

```bash
npm install -g mystmd
myst start
```

## Publish

Push to `main`. The workflow in `.github/workflows/deploy.yml` builds and deploys the site.
One-time setup: in the repository, go to **Settings → Pages → Build and deployment → Source** and choose **GitHub Actions**.
(This replaces the old `ghp-import` flow, so there is no manual publish step.)

## Before you publish: still to fill in

- A repository link for each case study (the old `[GitHub repo link]` rows were removed from the pages; add a `| **Repository** | [name](url) |` row to the table at the top of each notebook).
- `stock-candles-classification`: say where the 249 images came from and what classes 0, 1, and 2 mean.
- `visitor-tracker`: add a live demo link only after the consent notice is in place.
