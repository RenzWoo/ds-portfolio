# Portfolio

::::{grid} 1 1 2 2
:gutter: 3
:class-container: sd-align-major-center

:::{grid-item}
:columns: 12 12 4 4
```{image} images/u6PGO.jpg
:alt: Profile photo placeholder
:width: 200px
:align: center
```
:::

:::{grid-item}
:columns: 12 12 8 8
## Hi, I'm Renzo Alasan 🦾

**BS Data Science** · **University of Science and Technology of Southern Philippines**

📍 Quezon City, Philippines  
💻 [GitHub: @RenzWoo](https://github.com/RenzWoo) · 🔗 [LinkedIn](https://linkedin.com/in/YOUR-LINKEDIN-USERNAME) · ✉️ [your.email@example.com]
:::
::::

## About Me

I'm Renzo (**RenzWoo** on GitHub), a developer moving deeper into data science. I go all in on
the things I'm good at, and I build most of my work in private, so this portfolio is where
the finished pieces go public. I keep a simple daily habit: push at least one commit.


## Data Science Interests

- **Generative AI & retrieval systems:** grounding LLMs with curated data (RAG), semantic search, prompt engineering
- **Statistical inference & machine learning:** bootstrap methods, time-aware validation, feature selection, model tuning
- **Data engineering:** APIs, relational storage (SQLite/SQLAlchemy), pipelines, reproducible workflows
- **Visualization & storytelling:** geospatial maps, infographics, communicating uncertainty

## Skills & Tools

![Python](https://img.shields.io/badge/Python-0A0E1A?style=for-the-badge&logo=python&logoColor=4FC3F7)
![R](https://img.shields.io/badge/R-0A0E1A?style=for-the-badge&logo=r&logoColor=4FC3F7)
![JavaScript](https://img.shields.io/badge/JavaScript-0A0E1A?style=for-the-badge&logo=javascript&logoColor=4FC3F7)
![Java](https://img.shields.io/badge/Java-0A0E1A?style=for-the-badge&logo=openjdk&logoColor=4FC3F7)
![HTML5](https://img.shields.io/badge/HTML5-0A0E1A?style=for-the-badge&logo=html5&logoColor=4FC3F7)
![CSS3](https://img.shields.io/badge/CSS3-0A0E1A?style=for-the-badge&logo=css3&logoColor=4FC3F7)
![React](https://img.shields.io/badge/React-0A0E1A?style=for-the-badge&logo=react&logoColor=4FC3F7)
![Node.js](https://img.shields.io/badge/Node.js-0A0E1A?style=for-the-badge&logo=node.js&logoColor=4FC3F7)
![MongoDB](https://img.shields.io/badge/MongoDB-0A0E1A?style=for-the-badge&logo=mongodb&logoColor=4FC3F7)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0A0E1A?style=for-the-badge&logo=postgresql&logoColor=4FC3F7)

| Category | Tools |
|---|---|
| **Programming** | Python, R, JavaScript, Java |
| **Data Analysis & Statistics** | pandas, NumPy, tidyverse (dplyr, ggplot2), bootstrap resampling, ANOVA / mutual information |
| **Machine Learning** | scikit-learn, LightGBM, XGBoost, Optuna, sentence-transformers |
| **Generative AI** | Gemini API, prompt engineering, RAG pipelines |
| **Databases & Data Access** | SQLite, SQLAlchemy ORM, MongoDB, PostgreSQL, Kaggle API, MetaTrader 5 API |
| **Visualization & Geospatial** | Matplotlib, ggplot2, rayshader, sf, Leaflet |
| **Web / APIs** | FastAPI, Jinja2, React, Node.js, HTML/CSS |
| **Workflow** | Git & GitHub, Jupyter, R Markdown, Jupyter Book |
| **Currently learning** | [Add what you're picking up this semester] |

## Projects

Each page summarizes the problem, **how the data was sourced, stored, and preprocessed**, the method, results,
and honest limitations.

### 🤖 AI & Machine Learning

::::{grid} 1 1 2 2
:gutter: 3

:::{grid-item-card} SmartTrip CDO
:link: projects/smart-trip-cdo
:link-type: doc

A zero-cost **static RAG** system that turns a trip request into a grounded itinerary for Cagayan de Oro
using a curated 47-place database. Evaluated on 10 traveller scenarios.

+++
`RAG` `Gemini` `pandas` `prompt engineering`
:::

:::{grid-item-card} Market Direction Prediction
:link: projects/market-direction-ml
:link-type: doc

Forex bars from MetaTrader 5 → engineered features → volatility-scaled labels → tuned RF / LightGBM / XGBoost
with time-aware validation. Started as a chart-image CNN.

+++
`scikit-learn` `Optuna` `time series` `feature selection`
:::

:::{grid-item-card} Kaggle Dataset Finder
:link: projects/kaggle-dataset-finder
:link-type: doc

Describe the data you need in plain English; an LLM + embedding pipeline finds, downloads, and validates
matching Kaggle datasets by inspecting real columns and values.

+++
`Gemini` `sentence-transformers` `Kaggle API` `NLP`
:::
::::

### 📐 Statistics & Data Engineering

::::{grid} 1 1 2 2
:gutter: 3

:::{grid-item-card} Bootstrap Income Estimation
:link: projects/coffee-bootstrap
:link-type: doc

Compares parametric, percentile, and BCa confidence intervals on skewed coffee-farmer income, with
convergence, stress-test, and clustering analyses.

+++
`R` `bootstrap` `inference` `R Markdown`
:::

:::{grid-item-card} Visitor Geolocation Tracker
:link: projects/visitor-tracker
:link-type: doc

A FastAPI service that captures, enriches, and stores visit data in SQLite via SQLAlchemy, with an
authenticated admin dashboard and CSV export.

+++
`FastAPI` `SQLite` `SQLAlchemy` `REST API`
:::
::::

### 🗺️ Data Visualization

::::{grid} 1 1 2 2
:gutter: 3

:::{grid-item-card} U.S. Diabetes 3D Choropleth
:link: projects/diabetes-3d-map
:link-type: doc

County-level adult diabetes prevalence for the contiguous U.S. as a 3D extruded map, built from CDC and
Census data.

+++
`R` `sf` `rayshader` `geospatial`
:::

:::{grid-item-card} Philippine Volcanic Eruptions
:link: projects/volcanic-eruptions
:link-type: doc

Does explosivity predict deaths? An exploratory analysis and infographic of historical Philippine
eruptions.

+++
`R` `tidyverse` `EDA` `infographic`
:::
::::

*More projects will be added throughout the semester. See more of my code on
[GitHub](https://github.com/RenzWoo).*

## Get in Touch

I'm open to internships, collaborations, and conversations about data. Reach me at
**[your.email@example.com]**, on [LinkedIn](https://linkedin.com/in/YOUR-LINKEDIN-USERNAME),
or on [GitHub](https://github.com/RenzWoo).

---

```{epigraph}
I'm the only one who doesn't need to sleep.

-- probably me at 3am, debugging
```
