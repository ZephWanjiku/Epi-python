# CEMA Internship – Epidemiology Track Task

## Project Overview

This repository contains code and analysis for the Center for Epidemiological Modeling and Analysis (CEMA) internship task:  
**"Analyzing Regional Trends in Influenza-Like Illness (ILI) in Kenya: A Quantitative Epidemiology Case Study."**

The dataset includes:
- Year (2023–2024)
- Epidemiological week (`epi_week`)
- County
- Age categories (`age_group`)
- Percentage of outpatient visits due to ILI (`ili_percentage`)
- Estimated population for each age group in each county (`population`)

**Objective:**  
Evaluate temporal and county-specific ILI trends and interpret findings to inform public health decisions.

---

## Tasks & Approach

### a) Descriptive Analysis

1. **Mean ILI Percentage Table:**  
   - Compute the mean ILI percentage per county per year using groupby and aggregation.
2. **Weekly Trend Plot:**  
   - Visualize weekly ILI percentages across counties.
   - Identify peak ILI weeks and describe seasonal patterns.

### b) Epidemiological Measures

1. **Incidence Rate Calculation:**  
   - Calculate ILI incidence rates per 100,000 population for Nairobi, Kisumu, and Mombasa.
2. **Statistical Comparison:**  
   - Compare ILI percentages across the three counties using ANOVA and Kruskal-Wallis tests.

### c) Communicating Results

- Summarize findings in 5–10 sentences, incorporating key tables, charts, and interpretations.
- Discuss implications for public health response, such as targeted interventions and resource allocation.

---

## Usage

1. Place the dataset (`Epi_Task_Data.csv`) in the `Data/` directory.
2. Open `main.ipynb` in VS Code or Jupyter Notebook.
3. Run each cell sequentially to reproduce the analysis and visualizations.

---

## Key Findings

- Mean ILI percentages vary by county and year, indicating regional differences in disease burden.
- Weekly trend plots show seasonal peaks in ILI activity, especially between epidemiological weeks 3 and 5.
- Incidence rates per 100,000 population differ across Nairobi, Kisumu, and Mombasa.
- Statistical tests confirm significant differences in ILI percentages among counties.
- Visualizations (line and bar charts) effectively communicate these trends.
- Recommendations include prioritizing surveillance and vaccination during peak weeks and in high-incidence counties.

---

## Public Health Implications

The analysis supports targeted interventions and resource allocation to mitigate seasonal ILI surges. Enhanced surveillance and early warning systems can improve community health outcomes.

---

## Author

Zephania
