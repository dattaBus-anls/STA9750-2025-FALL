# 📊 STA 9750 — Software Tools & Data Analysis  
**Baruch College, City University of New York**

This repository contains my complete coursework for **STA 9750 (Software Tools & Data Analysis)**.  
All work is implemented as a **Quarto-based analytical website**, with reproducible R code, public data sources, and rendered HTML reports published via **GitHub Pages**.

The repository includes **four mini-projects** and a **final term project**, each focusing on real-world data problems, exploratory analysis, visualization, and clear communication.

---

## 👤 Author
**Apu Datta**  
Master of Science in Business Analytics  
Baruch College, CUNY  

---

## 🌐 Rendered Website (GitHub Pages)

All rendered HTML outputs are stored in the `docs/` directory, which serves as the GitHub Pages site.

- **Course Home:** `index.html`
- **Mini-Projects:**
  - `mp01.html`
  - `mp02.html`
  - `mp03.html`
  - `mp04.html`
- **Final Project:** Nightlife Analytics (linked via site navbar)

---

## 📁 Repository Structure

```text
STA9750-2025-FALL/
│
├── docs/                     # Rendered HTML outputs (GitHub Pages)
│   ├── mp01.html
│   ├── mp02.html
│   ├── mp03.html
│   └── mp04.html
│
├── Nightlife_Analytics/
│   └── quarto/
│       └── Nightlife_Analytics_covid(2019_2020_2023).qmd
│
├── mp01.qmd                  # Mini-Project 01 source
├── mp02.qmd                  # Mini-Project 02 source
├── mp03.qmd                  # Mini-Project 03 source
├── mp04.qmd                  # Mini-Project 04 source
│
├── index.qmd                 # Course landing page
├── about.qmd                 # About page
├── _quarto.yml               # Quarto site configuration & navbar
├── build_site.R              # Site build/render helper
│
├── images/                   # Images used across reports
├── styles.css                # Custom site styling
│
├── STA9750-2025-FALL.Rproj    # RStudio project file
└── README.md                 # Repository overview

## 🧪 Mini-Projects

### 🎬 Mini-Project 01 — Netflix Global Top 10 Analysis
- Focus: Global content reach and persistence on Netflix.
- Analyzes Netflix Global and Country Top 10 datasets
- Examines franchise durability, non-English content growth, and market momentum
- Emphasizes data cleaning, exploratory analysis, and interpretation

**📂 Files**
Source: mp01.qmd
Output: docs/mp01.html

### 🏠 Mini-Project 02 — Making Backyards Affordable for All (YIMBY Analysis)
- Focus: Housing affordability and development patterns across U.S. metro areas.
- Integrates ACS, BLS, and Census building-permit data
- Constructs affordability and growth indicators
- Communicates results in a policy-oriented narrative

**📂 Files**
Source: mp02.qmd
Output: docs/mp02.html

### 🌳 Mini-Project 03 — NYC Tree Canopy Analysis
- Focus: Distribution and condition of NYC’s urban forest.
- Uses NYC Open Data TreeMap and City Council district boundaries
- Performs geospatial joins and district-level summaries
- Proposes a data-informed NYC Parks policy intervention

**📂 Files**
Source: mp03.qmd
Output: docs/mp03.html

### 🧾 Mini-Project 04 — Just the Fact(-Check)s, Ma’am!
- Focus: Reliability of U.S. jobs numbers and employment revisions.
- Analyzes CES employment levels and revisions (1979–2025)
- Examines magnitude, direction, seasonality, and long-run trends
- Demonstrates statistical fact-checking using public data

**📂 Files**
Source: mp04.qmd
Output: docs/mp04.html

### 🌃 Final Project — Nightlife Analytics (NYC)

Research Question:
How does nightlife activity shape urban mobility and safety, and how did COVID-19 change night-time travel behavior in New York City?

🔑 Key Features
- TLC Yellow Taxi and FHV (Uber/Lyft) trip data (2019–2023)
- Focus on night-time trips (8 PM–4 AM)
- Yelp nightlife venue data
- Zone-level panel dataset built using DuckDB
- Comparison of pre-COVID (2019), COVID (2020), and post-COVID (2023)

#### ⭐ Key Finding
Night-time travel rebounded after COVID, but late-night travel (12–4 AM) remains persistently weaker, with activity shifting earlier in the evening—especially in nightlife-dense zones.

**📂 Files**
Source: Nightlife_Analytics/quarto/Nightlife_Analytics_covid(2019_2020_2023).qmd
Output: Published via the site navbar

### 🔁 Reproducibility Notes

- All analyses are implemented in R + Quarto
- Public datasets are acquired programmatically where possible
- Large raw datasets (e.g., TLC parquet files, API pulls) are cached locally and not fully included
- Rendered outputs are stored in docs/ for GitHub Pages hosting

### 🛠 Tools & Methods

- R, Quarto
- tidyverse, ggplot2, sf
- duckdb, plotly, DT
- httr2, rvest
- Public data APIs (NYC Open Data, BLS, Census, Yelp)

### 🌐 Web Links
- **GitHub Repository:** [STA9750-2025-FALL](https://github.com/dattaBus-anls/STA9750-2025-FALL)
- **Project Website:** [GitHub Pages](https://dattabus-anls.github.io/STA9750-2025-FALL/)
