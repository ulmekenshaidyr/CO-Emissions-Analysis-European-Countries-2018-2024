# CO₂ Emissions Analysis: European Countries 2018–2024

An exploratory data analysis of CO₂ emissions across 9 European countries from 2018 to 2024, examining per capita trends, total emissions over time, and the relationship between GDP and emissions intensity.

---

## Key Findings

- **All 9 countries reduced emissions** below their 2018 levels by 2024, consistent with progress toward SDG 13 (Climate Action)
- **Total CO₂ emissions declined by approximately 19–20%** across the selected countries between 2018 and 2024
- **2020 saw the sharpest single-year drop** (−10.3% YoY), driven by the COVID-19 pandemic and associated industrial slowdown
- **Netherlands made the most significant per capita improvement** among the top emitters, dropping from ~9.1 to ~6.3 tonnes per capita over 6 years
- **GDP alone is not a reliable predictor of per capita emissions** — energy mix, industrial structure, and climate policy play equally significant roles

---

## Charts

### 1. CO₂ per capita by country (2018–2024)
Line chart showing per capita emissions for all 9 countries. Two distinct clusters are visible: a high-emissions group (Netherlands, Norway, Germany) and a lower-emissions group (Italy, UK, Spain, Hungary, France, Switzerland).

### 2. Total CO₂ emissions with YoY growth (2018–2024)
Bar chart of combined emissions for all 9 countries, annotated with year-over-year percentage change. Highlights the COVID dip in 2020, the partial rebound in 2021, and the consistent decline from 2022 to 2024.

### 3. GDP vs CO₂ per capita correlation (2021)
Scatter plot examining whether wealthier countries emit more per capita. No strong linear correlation is found — mid-range GDP countries show highly varied emissions levels.

---

## Countries Analyzed

Germany, France, Italy, Norway, Netherlands, Switzerland, Hungary, Spain, United Kingdom

---

## Dataset

- **Source:** Our World in Data — CO₂ and Greenhouse Gas Emissions dataset
- **Repository:** https://github.com/ulmekenshaidyr/CO-Emissions-Analysis-European-Countries-2018-2024.git
- **File used:** `owid-co2-data.csv`
- **Years covered:** 2018–2024

---

## Tools & Libraries

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| pandas | Data loading, filtering, aggregation |
| numpy | Numerical operations |
| matplotlib | All visualizations |

---

## How to Run

1. Open the notebook on Kaggle: (https://www.kaggle.com/code/ulmekenshaidyr/notebook0ad06b046b)
2. The dataset is loaded directly from the OWID GitHub repository
3. Run all cells in order — no additional setup required

Alternatively, clone this repository and run locally:
```bash
pip install pandas numpy matplotlib
jupyter notebook CO2_Emissions_Analysis_European_Countries_2018_2024.ipynb
```

---

## Author

Ulmeken Shaidyr
- Environmental Engineering MSc
- [LinkedIn](#) *(add your LinkedIn URL)*
- [Kaggle](#) *(add your Kaggle profile URL)*

---

## Context

This project is part of a self-directed transition into climate data science, combining domain expertise in environmental and chemical engineering with applied data analysis skills. The focus on European emissions data reflects both personal background and professional interest in energy transition analytics.
