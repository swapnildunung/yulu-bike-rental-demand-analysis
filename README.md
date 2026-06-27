# 🚲 Yulu Bike Rental Demand Analysis

An end-to-end statistical analysis project using Hypothesis Testing, ANOVA, Chi-square Test and Exploratory Data Analysis (EDA) to identify factors influencing bike rental demand and support data-driven operational decisions.

---

## Project Overview

This project analyzes Yulu bike rental data to understand how weather, seasons and working days influence rental demand. Using hypothesis testing and statistical inference, the analysis validates key business assumptions and provides actionable recommendations for fleet planning, pricing and marketing strategies.

---

## Business Problem

Yulu aims to identify the key factors affecting bike rental demand and determine whether weather conditions, seasonal variations and working days significantly influence customer usage to optimize operational planning and customer engagement.

---

## Objectives

- Analyze rental demand across weather, season and working day segments.
- Perform exploratory data analysis to identify demand patterns.
- Apply statistical hypothesis testing to validate business assumptions.
- Evaluate seasonal and weather-related demand differences.
- Generate business recommendations for pricing, fleet allocation and marketing.

---

## Dataset

- **Domain:** Mobility / Bike Sharing
- **Records:** 10,886 hourly rental observations
- **Features:** Weather, season, holiday, working day, temperature, humidity, windspeed and rental count.

---

## Data Preparation

- Verified dataset quality and handled outlier analysis.
- Performed univariate and bivariate exploratory data analysis.
- Assessed normality and variance assumptions before statistical testing.
- Evaluated feature relationships using correlation analysis.

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Hypothesis Testing
- Two-Sample T-Test
- ANOVA & Tukey HSD
- Chi-square Test
- Statistical Inference
- Correlation Analysis
- Business Insight Generation

---

## Key Business Insights

- Working and non-working days show no meaningful difference in rental demand, with a negligible Cohen's d effect size of **0.025**.
- Rental demand varies significantly across seasons, with **Fall** recording the highest average demand and **Spring** the lowest.
- Demand declines substantially as weather conditions deteriorate, confirming weather as a major demand driver.
- Peak rentals occur during **8 AM** and **5–6 PM**, highlighting strong commuter usage patterns.
- Temperature positively influences rentals, while humidity negatively impacts demand, supporting weather-aware operational planning.

---

## Business Recommendations

- Implement weather-based pricing and promotional campaigns during adverse weather conditions.
- Increase fleet availability during morning and evening commuter peaks.
- Launch targeted campaigns during Spring to improve seasonal demand.
- Prioritize weather and seasonal variables for demand forecasting models.
- Focus marketing on demand patterns rather than working-day segmentation.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Google Colab

### Statistical Techniques

- Two-Sample T-Test
- ANOVA
- Tukey HSD
- Chi-square Test
- Correlation Analysis

---

## Note

The dataset is **not included** in this repository to comply with data usage and distribution restrictions.
