---
title: Data Science Portfolio
description: Machine learning, statistical inference, data engineering, and visualization projects by Renzo Alasan, with data sources, methods, results, and limitations.
---

<div class="hero">
<div class="hero-grid">
<div class="hero-text">
<span class="hero-pill">BS Data Science, USTP &bull; Smart Coder</span>
<h1 class="hero-main-title">Renzo Alasan</h1>
<p class="hero-sub">I build data pipelines and machine-learning models, then write up what worked, what didn't, and how I would test it better.</p>
<div class="hero-actions">
<a class="btn btn-primary" href="#projects">See the projects</a>
<a class="btn" href="https://github.com/RenzWoo" target="_blank" rel="noopener">GitHub</a>
<a class="btn" href="mailto:alasan.renzo123@gmail.com">Email me</a>
</div>
</div>
<div class="hero-avatar" role="img" aria-label="Profile photo of Renzo Alasan"></div>
</div>
</div>

<div class="ticker"><div class="ticker-track"><span class="ticker-item">Python</span><span class="ticker-item">R</span><span class="ticker-item">PyTorch</span><span class="ticker-item">scikit-learn</span><span class="ticker-item">LightGBM</span><span class="ticker-item">XGBoost</span><span class="ticker-item">Optuna</span><span class="ticker-item">pandas</span><span class="ticker-item">NumPy</span><span class="ticker-item">FastAPI</span><span class="ticker-item">SQLAlchemy</span><span class="ticker-item">SQLite</span><span class="ticker-item">Gemini API</span><span class="ticker-item">sentence-transformers</span><span class="ticker-item">ggplot2</span><span class="ticker-item">rayshader</span><span class="ticker-item">sf</span><span class="ticker-item">Jupyter</span><span class="ticker-item">MyST</span><span class="ticker-item ticker-dup">Python</span><span class="ticker-item ticker-dup">R</span><span class="ticker-item ticker-dup">PyTorch</span><span class="ticker-item ticker-dup">scikit-learn</span><span class="ticker-item ticker-dup">LightGBM</span><span class="ticker-item ticker-dup">XGBoost</span><span class="ticker-item ticker-dup">Optuna</span><span class="ticker-item ticker-dup">pandas</span><span class="ticker-item ticker-dup">NumPy</span><span class="ticker-item ticker-dup">FastAPI</span><span class="ticker-item ticker-dup">SQLAlchemy</span><span class="ticker-item ticker-dup">SQLite</span><span class="ticker-item ticker-dup">Gemini API</span><span class="ticker-item ticker-dup">sentence-transformers</span><span class="ticker-item ticker-dup">ggplot2</span><span class="ticker-item ticker-dup">rayshader</span><span class="ticker-item ticker-dup">sf</span><span class="ticker-item ticker-dup">Jupyter</span><span class="ticker-item ticker-dup">MyST</span></div></div>

(projects)=
## Featured Projects

<div class="bento-grid">
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-blue">Generative AI · RAG</span></div>
<h3 class="bento-card-title"><a href="projects/smart-trip-cdo.ipynb">SmartTrip CDO</a></h3>
<p class="bento-card-body">A zero-cost static RAG pipeline: an LLM parses the request, pandas retrieves places from a hand-curated Cagayan de Oro table, and the LLM writes the itinerary from those rows only. Reports where it misses its own targets.</p>
<div class="bento-stack"><i class="dot dot-py"></i>pandas · Gemini 2.5 Flash</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="projects/smart-trip-cdo.ipynb">Case Study &rarr;</a><div class="bento-links"></div></div>
</div>
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-violet">Machine Learning</span></div>
<h3 class="bento-card-title"><a href="projects/market-direction-ml.ipynb">Market Direction Prediction</a></h3>
<p class="bento-card-body">Forex bars from MetaTrader 5, engineered features, and volatility-scaled labels, with tuned Random Forest, LightGBM, and XGBoost under time-aware validation. The holdout shows little to no edge, and the page says so.</p>
<div class="bento-stack"><i class="dot dot-py"></i>scikit-learn · Optuna · LightGBM</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="projects/market-direction-ml.ipynb">Case Study &rarr;</a><div class="bento-links"></div></div>
</div>
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-blue">NLP · Generative AI</span></div>
<h3 class="bento-card-title"><a href="projects/kaggle-dataset-finder.ipynb">Kaggle Dataset Finder</a></h3>
<p class="bento-card-body">Describe the data you need in plain English. An LLM and sentence embeddings shortlist Kaggle datasets, then a second pass checks the real column names and sample values.</p>
<div class="bento-stack"><i class="dot dot-py"></i>Gemini · sentence-transformers · Kaggle API</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="projects/kaggle-dataset-finder.ipynb">Case Study &rarr;</a><div class="bento-links"></div></div>
</div>
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-green">Statistical Inference</span></div>
<h3 class="bento-card-title"><a href="projects/coffee-bootstrap.ipynb">Bootstrap Income Estimation</a></h3>
<p class="bento-card-body">Parametric, percentile, and BCa confidence intervals on skewed coffee-farmer income, with a convergence study, stress tests, a block bootstrap, and subgroup intervals.</p>
<div class="bento-stack"><i class="dot dot-r"></i>R · boot · ggplot2</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="projects/coffee-bootstrap.ipynb">Case Study &rarr;</a><div class="bento-links"></div></div>
</div>
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-green">Data Engineering</span></div>
<h3 class="bento-card-title"><a href="projects/visitor-tracker.ipynb">Visitor Geolocation Tracker</a></h3>
<p class="bento-card-body">A FastAPI service that captures, enriches, and stores visit data in SQLite through SQLAlchemy, with a protected admin area, CSV export, and a privacy and consent section.</p>
<div class="bento-stack"><i class="dot dot-py"></i>FastAPI · SQLAlchemy · SQLite</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="projects/visitor-tracker.ipynb">Case Study &rarr;</a><div class="bento-links"><a class="bento-sublink" href="https://wifi-location-tracker.onrender.com" target="_blank" rel="noopener">Live App &nearr;</a></div></div>
</div>
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-rose">Geospatial · Visualization</span></div>
<h3 class="bento-card-title"><a href="projects/diabetes-3d-map.ipynb">U.S. Diabetes 3D Choropleth</a></h3>
<p class="bento-card-body">County-level adult diabetes prevalence for the contiguous U.S. as a ray-traced 3D map. It separates how many people have diabetes from what share of people do.</p>
<div class="bento-stack"><i class="dot dot-r"></i>R · sf · rayshader</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="projects/diabetes-3d-map.ipynb">Case Study &rarr;</a><div class="bento-links"></div></div>
</div>
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-rose">EDA · Data Storytelling</span></div>
<h3 class="bento-card-title"><a href="projects/volcanic-eruptions.ipynb">Philippine Volcanic Eruptions</a></h3>
<p class="bento-card-body">Does explosivity predict deaths? An exploratory analysis and infographic, with a sensitivity check showing how much the answer moves with the selection rule.</p>
<div class="bento-stack"><i class="dot dot-r"></i>R · tidyverse · ggplot2</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="projects/volcanic-eruptions.ipynb">Case Study &rarr;</a><div class="bento-links"></div></div>
</div>
</div>

## Deep Learning Laboratory Activities

<div class="bento-grid bento-grid-3">
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-violet">LAB TASK 1</span></div>
<h3 class="bento-card-title"><a href="labs/lab-task-1.ipynb">Laboratory Task 1: Four Types of Data Analytics</a></h3>
<p class="bento-card-body">Two inquiries for each type of data analytics (descriptive, diagnostic, predictive, prescriptive), written for the Dr. Jake and Astro JR COVID-19 vaccine scenario.</p>
<div class="bento-stack">Descriptive · Diagnostic · Predictive · Prescriptive</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="labs/lab-task-1.ipynb">Open Notebook &rarr;</a><div class="bento-links"></div></div>
</div>
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-violet">LAB TASK 2</span></div>
<h3 class="bento-card-title"><a href="labs/lab-task-2.ipynb">Laboratory Task 2: Forward Pass and Error by Hand</a></h3>
<p class="bento-card-body">A single forward pass through a 3-2-1 network with ReLU, worked step by step and checked in NumPy. The prediction is 0.08 against a target of 1, an error of &minus;0.92.</p>
<div class="bento-stack"><i class="dot dot-py"></i>Hand computation · NumPy</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="labs/lab-task-2.ipynb">Open Notebook &rarr;</a><div class="bento-links"></div></div>
</div>
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-violet">LAB TASKS 3 &amp; 4</span></div>
<h3 class="bento-card-title"><a href="labs/lab-tasks-3-4.ipynb">Laboratory Tasks 3 and 4: Backpropagation and Linear Regression</a></h3>
<p class="bento-card-body">Task 3: forward and backward propagation in NumPy on the Task 2 network (ReLU, learning rate 0.001). Task 4: a two-layer linear regression in PyTorch on the scikit-learn Diabetes data (MSE, SGD, batch size 8, 1,000 epochs), reaching a test R&sup2; of 0.45.</p>
<div class="bento-stack"><i class="dot dot-py"></i>NumPy · PyTorch · scikit-learn</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="labs/lab-tasks-3-4.ipynb">Open Notebook &rarr;</a><div class="bento-links"></div></div>
</div>
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-violet">LAB TASK 5</span></div>
<h3 class="bento-card-title"><a href="labs/lab-task-5.ipynb">Laboratory Task 5: PyTorch Tensor Basics</a></h3>
<p class="bento-card-body">Ten short exercises: seeding, NumPy-to-tensor conversion, changing dtype, reshaping, slicing, squaring without modifying the tensor, and matrix multiplication.</p>
<div class="bento-stack"><i class="dot dot-py"></i>PyTorch · NumPy</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="labs/lab-task-5.ipynb">Open Notebook &rarr;</a><div class="bento-links"></div></div>
</div>
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-violet">LAB TASK 6</span></div>
<h3 class="bento-card-title"><a href="labs/lab-task-6.ipynb">Laboratory Task 6: CNN Architecture in PyTorch</a></h3>
<p class="bento-card-body">Converts a CNN architecture diagram into a PyTorch module: four 3&times;3 convolutions, two max-pool layers, and three fully connected layers (13.4 million parameters), with layer-by-layer shape checks.</p>
<div class="bento-stack"><i class="dot dot-py"></i>PyTorch · torch.nn</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="labs/lab-task-6.ipynb">Open Notebook &rarr;</a><div class="bento-links"></div></div>
</div>
</div>

## Deep Learning Laboratory Exercises

<div class="bento-grid">
<div class="bento-card">
<div>
<div class="bento-card-header"><span class="bento-tag tag-violet">LAB EXERCISE 1</span></div>
<h3 class="bento-card-title"><a href="projects/stock-candles-classification.ipynb">Stock Candlestick Classification</a></h3>
<p class="bento-card-body">Five pre-trained torchvision models fine-tuned on 249 candlestick chart images with a 70/30 split. The results are close to a majority-class guess, and the page explains why.</p>
<div class="bento-stack"><i class="dot dot-py"></i>PyTorch · torchvision</div>
</div>
<div class="bento-card-footer"><a class="bento-link" href="projects/stock-candles-classification.ipynb">Open Notebook &rarr;</a><div class="bento-links"></div></div>
</div>
</div>

## How each project is written up

<div class="stats-grid">
<div class="stat-card"><div class="stat-label">Where the data came from</div><div class="stat-desc">Source, size, and whether it is real or synthetic.</div></div>
<div class="stat-card"><div class="stat-label">How it was cleaned and stored</div><div class="stat-desc">Formats, joins, missing values, and anything that could leak.</div></div>
<div class="stat-card"><div class="stat-label">What the results show</div><div class="stat-desc">Numbers with context, including the ones that missed their target.</div></div>
<div class="stat-card"><div class="stat-label">What would make it better</div><div class="stat-desc">The next test I would run, in plain language.</div></div>
</div>

## Skills

Grouped by what the projects above actually use. The last group is what I work with outside these write-ups.

<div class="skill-groups">
<div class="skill-group">
<p class="skill-title">Languages</p>
<div class="chips"><span class="chip">Python</span><span class="chip">R</span></div>
</div>
<div class="skill-group">
<p class="skill-title">Machine learning</p>
<div class="chips"><span class="chip">scikit-learn</span><span class="chip">LightGBM</span><span class="chip">XGBoost</span><span class="chip">Optuna</span><span class="chip">PyTorch</span><span class="chip">torchvision</span><span class="chip">sentence-transformers</span></div>
</div>
<div class="skill-group">
<p class="skill-title">Generative AI</p>
<div class="chips"><span class="chip">Gemini API</span><span class="chip">RAG pipelines</span><span class="chip">Prompt engineering</span></div>
</div>
<div class="skill-group">
<p class="skill-title">Statistics</p>
<div class="chips"><span class="chip">Bootstrap (percentile, BCa)</span><span class="chip">ANOVA</span><span class="chip">Mutual information</span><span class="chip">Time-aware validation</span></div>
</div>
<div class="skill-group">
<p class="skill-title">Data and APIs</p>
<div class="chips"><span class="chip">pandas</span><span class="chip">NumPy</span><span class="chip">SQLite</span><span class="chip">SQLAlchemy</span><span class="chip">FastAPI</span><span class="chip">Kaggle API</span><span class="chip">MetaTrader 5 API</span></div>
</div>
<div class="skill-group">
<p class="skill-title">Visualization</p>
<div class="chips"><span class="chip">Matplotlib</span><span class="chip">ggplot2</span><span class="chip">rayshader</span><span class="chip">sf</span><span class="chip">Leaflet</span></div>
</div>
<div class="skill-group">
<p class="skill-title">Workflow</p>
<div class="chips"><span class="chip">Git and GitHub</span><span class="chip">Jupyter</span><span class="chip">R Markdown</span><span class="chip">MyST</span></div>
</div>
<div class="skill-group">
<p class="skill-title">Also work with</p>
<div class="chips"><span class="chip">JavaScript</span><span class="chip">Java</span><span class="chip">HTML and CSS</span><span class="chip">React</span><span class="chip">Node.js</span><span class="chip">MongoDB</span><span class="chip">PostgreSQL</span></div>
</div>
</div>

## About

I'm Renzo (**RenzWoo** on GitHub), a developer moving deeper into data science. I'm a BS Data Science student at the University of Science and Technology of Southern Philippines, based in Quezon City. Most of my work stays in private repositories, so this site is where finished pieces go public. I keep one daily habit: push at least one commit.

My interests are generative AI and retrieval systems, statistical inference and machine learning, data engineering, and visualization that communicates uncertainty honestly.

## Get in touch

I'm open to internships, collaborations, and conversations about data. Email me at **[alasan.renzo123@gmail.com](mailto:alasan.renzo123@gmail.com)** or browse my code on [GitHub](https://github.com/RenzWoo).

*"I'm the only one who doesn't need to sleep." Probably me at 3am, debugging.*

---

```{tableofcontents}
```
