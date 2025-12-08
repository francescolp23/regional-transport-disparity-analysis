# Regional Transport Disparity Analysis

![Language](https://img.shields.io/badge/Language-Python-blue)
![Course](https://img.shields.io/badge/Course-Big%20Data%20for%20Official%20Statistics-green)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

> **Big Data for Official Statistics project:** application of unsupervised learning models to map regional infrastructure gaps and guide targeted ministerial interventions.

## 📌 Project Overview
Infrastructure inequality is a critical national challenge.
**The Scenario:** The Ministry aims to optimize resource allocation to minimize regional gaps. To address this, we leverage Big Data to map urban disparities and network vulnerabilities. By integrating socio-economic indices, our analysis identifies critical areas to support **evidence-based policymaking**.

### Key Objectives
1.  **Data Collection:** Aggregate official statistics on transport infrastructures (Urban/Non-Urban) and socio-economic indicators.
2.  **Clustering Analysis:** Apply unsupervised learning (K-Means, Hierarchical) to group regions based on infrastructure endowment.
3.  **Policy Insights:** Provide data-driven recommendations to reduce regional disparities.

## 📊 Data Sources
This project relies on **Official Statistics** and Open Data. Primary sources include:
* **ISTAT:** [Inserire qui specifici dataset, es. "Capacità degli esercizi ricettivi", "Infrastrutture viarie"]
* **Ministero delle Infrastrutture e dei Trasporti (MIT):** Open data on transport networks.
* **Eurostat:** Regional benchmarks (NUTS 2 level).

## 🛠️ Methodology
The analysis follows a standard Data Science pipeline:
1.  **Data Cleaning & Preprocessing:** Handling missing values, normalization of socio-economic indices.
2.  **Exploratory Data Analysis (EDA):** Visualizing geographical distributions of transport nodes.
3.  **Dimensionality Reduction:** PCA (Principal Component Analysis) to manage high-dimensional official data.
4.  **Clustering:**
    * *K-Means* to identify macro-groups of regions.
    * *Hierarchical Clustering* to detect sub-regional similarities.

## 📂 Repository Structure
```text
├── data/
│   ├── raw/             # Original official datasets (immutable)
│   ├── processed/       # Cleaned data ready for analysis
│   └── external/        # Socio-economic auxiliary data
├── notebooks/           # Jupyter Notebooks for EDA and Clustering
├── src/                 # Source code for data processing and models
├── reports/             # Generated analysis and figures
└── README.md
