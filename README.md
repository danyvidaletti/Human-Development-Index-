# Human Development Index (HDI) Analysis – Brazil 2010
## Storytelling with Data: Mapping Inequality Across 5,564 Municipalities

This repository contains a comprehensive data analysis of the **Municipal Human Development Index (MHDI)** for all 5,564 Brazilian municipalities, based on the 2010 Demographic Census. The project explores the three pillars of human development—**Education, Longevity, and Income**—to highlight regional inequalities and identify statistical drivers of development.

---

## 📌 Project Overview

Brazil is a country of continental proportions and deep structural contrasts. This analysis decomposes the MHDI to tell the story of a nation divided: a prosperous South and Southeast juxtaposed with a structurally underdeveloped North and Northeast.

### Research Questions
1. **Distribution & Inequality:** How was human development distributed across Brazil in 2010, and what do the gaps between averages and medians tell us about inequality?
2. **Pillar Impact:** Which pillar (Health, Education, or Income) has the strongest statistical relationship with the overall MHDI?
3. **Regional Outliers:** Which municipalities perform significantly better (or worse) than their regional peers?

---

## 🛠️ Tech Stack

The analysis was performed using **Python** and the following data science libraries:
* **Pandas:** Data manipulation and aggregation.
* **NumPy:** Numerical operations and array handling.
* **Matplotlib & Seaborn:** Static data visualizations and statistical plotting.
* **Plotly Express:** Interactive state-level visualizations.
* **Scikit-Learn:** Linear regression modeling to determine pillar weights.

---

## 📊 Methodology & Analysis Flow

The project follows a structured data science pipeline:
1. **Environment Setup:** Loading dependencies and configuring plot styles.
2. **Data Loading:** Importing data from the *Atlas do Desenvolvimento Humano no Brasil* (UNDP/IPEA/FJP).
3. **Data Cleaning:** Handling missing values and ensuring data type consistency.
4. **National Analysis:** Establishing a baseline for the country.
5. **Regional & State Analysis:** Comparing the five macro-regions and individual states.
6. **Pillar Deep Dive:** Analyzing the specific correlations of Education, Longevity, and Income.
7. **Statistical Modeling:** Using Linear Regression to quantify the impact of each sub-index.
8. **Outlier Identification:** Identifying "islands of development" in underprivileged regions.

---

## 📈 Key Findings

* **Regional Divide:** A clear "North-South" divide is evident, with the South and Southeast regions consistently outperforming the North and Northeast.
* **Education as a Bottleneck:** Education often presents the lowest scores among the three pillars, acting as a primary constraint on overall municipal development.
* **Predictive Power:** Statistical modeling reveals how heavily each pillar influences the final MHDI, helping prioritize policy interventions.
* **Island Effect:** Certain municipalities in the North/Northeast act as "islands" of high development relative to their surrounding regional context.

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/hdi-analysis-brazil.git](https://github.com/your-username/hdi-analysis-brazil.git)
