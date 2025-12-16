# Regional Transport Infrastructure Disparity Analysis (Italy)

🔗 **Link to code (Google Colab):**  
https://colab.research.google.com/drive/1-Cf8LBcOAszpwjHuEN9RO9QVz5W9jDgF?usp=sharing  

![Language](https://img.shields.io/badge/Language-Python-blue)
![Course](https://img.shields.io/badge/Course-Big%20Data%20for%20Official%20Statistics-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **Big Data for Official Statistics – Academic Project**  
> Application of unsupervised learning to identify regional transport infrastructure disparities and support cluster-oriented public policy interventions.

---

## 📌 Project Overview

Transport infrastructure inequality represents a key structural challenge for Italy.  
This project addresses the problem from an **official statistics and data-driven policy** perspective.

**Goal:**  
Support government decision-making by identifying *homogeneous regional clusters* in terms of transport infrastructure endowment, accessibility, and mobility performance, using **official ISTAT data** complemented by **big data sources**.

Rather than funding regions individually, the project proposes a **cluster-based policy framework**, where interventions target structural needs shared across territories.

---

## 🎯 Objectives

1. **Collect and integrate official transport-related statistics** at the regional level.
2. **Explore and validate data quality** through EDA and correlation analysis.
3. **Identify regional clusters** using unsupervised learning techniques.
4. **Interpret clusters from a policy perspective**, highlighting structural weaknesses and strengths.
5. **Validate results** using selected ISTAT regional indicators.
6. **Compare official statistics with Big Data evidence** to assess consistency and limitations.

---

## 📊 Data Sources

The analysis is grounded in **Official Statistics**, ensuring coherence with institutional and policy-oriented goals.

### Main Sources
- **ISTAT** (Italian National Institute of Statistics)  
  - Mobility of workers and students  
  - Freight transport  
  - Railway infrastructure  
  - Accessibility and transport-related indicators  
- **ISTAT Regional Indicators**  
  - Real GDP per capita  
  - Traffic congestion discomfort  
  - Road condition discomfort  

### Big Data (Support Analysis)
- **OpenStreetMap**  
  - Road network  
  - Railway network  

> Big Data are used **only as a complementary validation tool**, not as a replacement for official statistics.

---

## 🧪 Methodology

The project follows a structured **Data Science pipeline**, aligned with the principles of Official Statistics.

### 1. Data Preparation
- Regional-level aggregation
- Handling missing values
- Feature normalization and standardization

### 2. Exploratory Data Analysis (EDA)
- Descriptive statistics
- Boxplots to identify dispersion and outliers
- Correlation matrix analysis  
  - Moderate multicollinearity detected and retained after domain-based evaluation

### 3. Clustering Analysis
- **K-Means clustering**
- Selection of the number of clusters using:
  - Elbow Method
  - Silhouette Score
- Final choice: **k = 6**, to allow finer policy-oriented interpretation

### 4. Dimensionality Reduction
- **Principal Component Analysis (PCA)**
- 2D and 3D visualizations for cluster inspection and interpretation

### 5. Cluster Interpretation
Clusters are interpreted **structurally**, not geographically, and labeled according to dominant characteristics.

---

## 📌 Main Results

The analysis identifies **six clusters**, including both regular and anomalous cases.

### Key Cluster Typologies

- **Metropolitan / Congestion Cluster**  
  - High infrastructure endowment and GDP  
  - Strong mobility performance  
  - Critical congestion and saturation issues  
  - Policy focus: decongestion, green transition

- **Structural Efficiency Cluster**  
  - Moderate development  
  - Weaknesses in rail and intermodal logistics  
  - Policy focus: efficiency and network optimization

- **Maintenance & Continuity Cluster**  
  - Generally well-developed regions  
  - Need for targeted interventions (maintenance, electrification, continuity)

- **Isolation Cluster**  
  - Internal and peripheral regions  
  - Low accessibility and connectivity  
  - Low congestion but structural isolation  
  - Policy focus: demand-responsive transport, digitalization, social mobility

Some clusters are **anomalous**, composed of one or two regions with unique structural profiles, and are treated separately.

---

## 📈 Regional Indicators Validation

To strengthen policy relevance, clusters are compared with selected **ISTAT regional indicators**:

- **Real GDP per capita**
- **Traffic congestion discomfort**
- **Road condition discomfort**

### Key Insights
- High GDP clusters also show **higher congestion and infrastructure saturation**
- Low GDP clusters exhibit **low congestion but structural isolation**
- Slightly better road-condition indicators in isolated areas reflect **underuse rather than efficiency**

This confirms that **wealth often produces saturation**, while fragility manifests as isolation rather than congestion.

---

## 🌐 Big Data Comparison

Big Data from OpenStreetMap are used to assess whether network-based evidence aligns with official statistics.

- Results show **partial consistency** with official clustering
- Differences are expected due to:
  - Limited feature scope (only road and rail networks)
  - Lack of socio-economic dimensions
  - Lower reliability compared to official data

**Conclusion:** Big Data can support but not replace Official Statistics in policy-oriented analysis.

---

## 🏁 Key Takeaway

> *There is no single infrastructure policy for Italy.*

Public investments should not target regions as isolated entities, but rather **structural clusters**, wherever they are geographically located.

**Policy implication:**  
PNRR and structural funds should be **cluster-oriented**:
- Green transition for urban hubs  
- Competitiveness for productive areas  
- Cohesion and accessibility for fragile and isolated territories  

---

## 📚 Course Context

- **Course:** Big Data for Official Statistics  
- **Focus:** Integration of data science methods with institutional statistics  
- **Approach:** Methodological rigor, interpretability, and policy relevance  

---

## 👤 Author

Academic projec
