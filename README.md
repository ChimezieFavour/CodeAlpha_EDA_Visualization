# Exploratory Data Analysis & Visualization — Diabetes Dataset

## Project Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) 
and Data Visualization on the Pima Indians Diabetes Dataset. The goal 
is to uncover patterns, relationships, and key risk factors associated 
with diabetes through statistical analysis and compelling visualizations.

This project was completed as part of my Data Analytics internship 
at **CodeAlpha**.

---

## Dataset
- **Name:** Pima Indians Diabetes Database
- **Source:** [Kaggle — UCI Machine Learning](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Size:** 768 patients, 9 columns
- **Population:** Female patients of Pima Indian heritage, aged 21+

> The dataset is not uploaded to this repository due to its size.
> Please download it directly from the Kaggle link above.

---

## Tools & Libraries
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

## Project Workflow
1. **Data Loading** — Loaded and previewed the dataset structure
2. **Data Cleaning** — Identified and replaced medically impossible 
zero values in Glucose, BloodPressure, SkinThickness, Insulin and BMI 
columns with column medians
3. **Statistical Summary** — Generated descriptive statistics across 
all health metrics
4. **EDA** — Explored distributions, correlations, and relationships 
between health variables and diabetes outcome
5. **Visualization** — Created five comprehensive charts to communicate 
findings visually

---

## Key Findings

- **35% of patients in the dataset are diabetic**
- **Glucose is the strongest diabetes predictor** (correlation: 0.49) 
— diabetic patients averaged 142.1 vs 110.7 for non-diabetic patients
- **BMI is the second strongest predictor** (correlation: 0.31) 
— diabetic patients averaged BMI 35.4 vs 30.9
- **Age matters significantly** — diabetic patients averaged 37.1 years 
vs 31.2 years for non-diabetic patients
- **Blood pressure showed the weakest association** with diabetes 
outcome among all metrics
- **374 insulin values and 227 skin thickness values** were recorded 
as zero — medically impossible values that required cleaning before 
analysis

---

## Visualizations
All charts are saved in the `/charts` folder:
- `1_outcome_distribution.png` — Diabetic vs Non-Diabetic patient count
- `2_distributions.png` — Distribution of all health metrics by outcome
- `3_correlation_heatmap.png` — Correlation matrix of all health metrics
- `4_boxplots.png` — Health metric comparisons by diabetes outcome
- `5_pairplot.png` — Pairwise relationships across all health metrics

---

## Author
**Favour** — Data Analytics Intern at CodeAlpha
