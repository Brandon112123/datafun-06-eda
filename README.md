# Exploratory Data Analysis (EDA) – Car Crash Dataset

Author: Brandon Deshaun Smith  
Northwest Missouri State University  
MS in Data Analytics  
Date: 2026  

---

## Overview

This project analyzes the Seaborn Car Crash dataset to examine the relationship between alcohol involvement and total fatal crash rates across U.S. states.

---

## Tools

- Python 3  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- VS Code  
- Git / GitHub  

---

## Push to GitHub

```bash
git add .
git commit -m "Update EDA analysis"
git push origin main
```

---

## Dataset Information

**Source:**  
https://github.com/mwaskom/seaborn-data/blob/master/car_crashes.csv  

### Dataset Size

| Item | Value |
|------|-------|
| Records | 51 (50 states + DC) |
| Columns | 8 |
| Type | Cross-sectional state data |

### Column Descriptions

| Column | Description |
|--------|-------------|
| total | Fatal collision rate per billion miles driven |
| speeding | % of drivers speeding in fatal crashes |
| alcohol | % of drivers over legal BAC in fatal crashes |
| not_distracted | % of drivers not distracted |
| no_previous | % with no prior violations |
| ins_premium | Average annual insurance premium (USD) |
| ins_losses | Average insurance losses per driver (USD) |
| abbrev | State abbreviation |

---

## Research Question

Is there a relationship between alcohol involvement and total fatal crash rates?

---

## Method

- Data inspection  
- Pearson correlation  
- Scatterplot with regression line  

---

## Findings

Alcohol shows a positive relationship with total crash rates. States with higher alcohol-related crash percentages generally have higher overall fatal crash rates.

---

## Conclusion

Alcohol appears to be a meaningful contributor to fatal crash rates, though other variables may also play a role.
