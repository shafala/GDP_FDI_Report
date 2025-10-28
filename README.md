# GDP_FDI_Report
Econometrics report: FDI vs GDP growth (R)

# GDP_FDI_Report — Econometrics Analysis (R)

This project explores the relationship between **Foreign Direct Investment (FDI)** and **GDP growth** for European countries using **World Bank (2020)** data.  
The analysis includes descriptive statistics, visualisations, correlation analysis, and a simple linear regression model using R.

---

## 📘 Overview

This study examines whether FDI inflows (% of GDP) are related to GDP growth (annual %).  
It performs data management, descriptive statistics, visualisations, and regression analysis entirely in **RStudio**.

---

## 🧠 Key Findings

- Average GDP growth ≈ **–4.1 %** in 2020, reflecting COVID-19’s economic impact.  
- FDI shows **very high variability** (SD ≈ 58) and several outliers.  
- Correlation between FDI and GDP growth is **–0.02**, indicating almost no linear relationship.  
- Simple OLS regression finds FDI has **no significant effect** on GDP growth (p = 0.915, R² = 0.0003).

## ⚙️ Tools Used

**Primary Environment**
- [RStudio](https://posit.co/download/rstudio-desktop/) (IDE for R)

**R Packages**
- `readxl` — import Excel data  
- Base R functions for summary statistics (`summary()`, `sd()`)  
- `apply_labels` — add variable labels for clarity  
- Base R plotting functions (`hist()`, `plot()`, `abline()`) for visualisations  
- Built-in regression tools (`lm()`, `summary()`) for OLS estimation  
- `write.csv()` — export results tables  
- Optional: tidyverse or ggplot2 for future visualisation improvements

---

## 🧾 Main Steps (as in the report)

1. **Data Management**
   - Converted GDP growth from proportions to percentages (`GDP <- GDP1 * 100`)
   - Labeled variables and sorted dataset by FDI  
   - Saved processed datasets for reuse
  
2. **Descriptive Statistics**
   - Calculated mean, median, quartiles, and standard deviations for FDI, GDP, and inflation  
   - Exported summary table to CSV  

3. **Visualisations**
   - Created histograms for GDP, FDI, and inflation  
   - Generated scatter plot of GDP vs FDI  

4. **Relationship Analysis**
   - Computed covariance and correlation between GDP and FDI  
   - Exported covariance/correlation table to CSV  

5. **Regression Analysis**
   - Estimated simple linear model `GDP ~ FDI`  
   - Summarised results (coefficients, p-values, R²)  
   - Exported regression output to CSV  

---

## 📂 Contents

| File | Description |
|------|--------------|
| **GDP_FDI_Report.pdf** | Full econometrics report with results and code appendix |

## 👤 Author

**Asal Shafie** — BSc Economics student, Aston University, UK  
*“Exploring data and econometrics with RStudio to understand real-world economic patterns.”*
