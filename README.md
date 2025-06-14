# Eurostat Employment Analysis – Finland (NUTS 3 Regions)

This repository contains a university semester project focused on analyzing employment data from [Eurostat](https://ec.europa.eu/eurostat/databrowser/view/nama_10r_3empers/default/table) for **Finland** in 2022. The data is categorized by **NUTS 3 administrative regions** and **NACE economic sectors**, focusing on employed persons (wstatus = "EMP").

## 📊 Dataset

* **ID:** `nama_10r_3empers`
* **Title:** Employment by NUTS 3 region
* **Focus:** Employment in thousands by region and sector (grouped into A–F, G–J, K–N, O–U)
* **Country analyzed:** Finland
* **Year:** 2022 (or closest available year without NA values)

## 📌 Project Tasks

### 1. Descriptive Statistics

* Summary of the dataset structure and key variables
* Core statistical measures (mean, median, min, max, etc.)
* Visualizations (bar plots, boxplots, heatmaps, etc.)

### 2. Contingency Table & Hypothesis Testing

* Cross-tabulation of employment by region and sector
* Chi-squared test of independence
* Interpretation of the result and its implications

### 3. Statistical Hypothesis Testing

* Formulation of 3 hypothesis pairs (H₀ and H₁)
* Use of various statistical tests (e.g., t-test, ANOVA, correlation)
* Justification, execution, and interpretation of each test

## 🧠 Techniques & Tools Used

* Data preprocessing and aggregation
* Statistical testing using R's built-in functions and stats package
* Hypothesis testing (parametric and non-parametric)
* Exploratory data analysis using base R, tidyverse, and ggplot2
