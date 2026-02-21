# Exploratory Data Analysis (EDA) – Car Crash Dataset

Author: Brandon Deshaun Smith  
Master of Science in Data Analytics Candidate  
Northwest Missouri State University  
Course: Data Analytics  
Project Type: Exploratory Data Analysis  
Date: 2026  

------------------------------------------------------------

## Project Overview

This repository contains a structured exploratory data analysis (EDA) of the Seaborn Car Crash dataset.  
The objective of this project is to analyze the relationship between alcohol involvement and total fatal crash rates across U.S. states.

This project demonstrates:

• Data inspection and summary statistics  
• Correlation analysis  
• Data visualization  
• Interpretation of statistical relationships  
• Professional repository documentation practices  

------------------------------------------------------------

## Environment & Tools

Programming Language: Python 3  

Libraries Used:  
• pandas  
• numpy  
• matplotlib  
• seaborn  

Development Environment:  
• VS Code  
• Git  
• GitHub  

------------------------------------------------------------

## Local Push to GitHub

git add .
git commit -m "Update EDA analysis"
git push origin main

------------------------------------------------------------

## Dataset Information

Dataset Name: Car Crash Dataset  
Source: Seaborn Data Repository  
https://github.com/mwaskom/seaborn-data/blob/master/car_crashes.csv  

This dataset contains automobile insurance and fatal collision statistics for:

• 50 U.S. states  
• District of Columbia  
• 51 total records  

Each row represents one state (or D.C.), and each column represents a crash-related metric.

------------------------------------------------------------

## Dataset Size

Records: 51 rows  
Columns: 8 columns  
Type: Cross-sectional state-level data  

------------------------------------------------------------

## Column Descriptions

total  
Total fatal collision rate per billion miles driven  

speeding  
Percentage of drivers involved in fatal collisions who were speeding  

alcohol  
Percentage of drivers involved in fatal collisions who had a blood alcohol level above the legal limit  

not_distracted  
Percentage of drivers in fatal collisions who were not distracted  

no_previous  
Percentage of drivers involved in fatal collisions with no previous accidents or violations  

ins_premium  
Average annual car insurance premium in the state (USD)  

ins_losses  
Average insurance losses per insured driver in the state (USD)  

abbrev  
Two-letter postal abbreviation for the state  

------------------------------------------------------------

## Research Question

Does alcohol involvement have a measurable relationship with total crash percentage across U.S. states?

This analysis investigates whether states with higher alcohol-related crash percentages also experience higher total fatal crash rates.

------------------------------------------------------------

## Exploratory Data Analysis Process

The analysis includes:

• Dataset inspection (head, info, describe)  
• Correlation calculation using Pearson correlation coefficient  
• Scatterplot visualization  
• Regression trend line analysis  
• Identification of high-alcohol states  
• Interpretation of statistical findings  

------------------------------------------------------------

## Key Findings

• Alcohol involvement shows a positive relationship with total crash rates.  
• States with higher alcohol-related crash percentages generally have higher overall fatal crash rates.  
• Alcohol appears to be a meaningful contributing factor to fatal collisions.  
• Additional variables such as speeding may also influence crash rates and warrant further analysis.  

------------------------------------------------------------

## Reproducibility

To reproduce this analysis:

1. Clone the repository  
2. Create a virtual environment  
3. Install dependencies  
4. Run the notebook  

Example setup:

python -m venv .venv  
source .venv/bin/activate   (Mac/Linux)  
.venv\Scripts\activate      (Windows)  
pip install pandas numpy matplotlib seaborn  

------------------------------------------------------------

## Conclusion

The exploratory analysis suggests that alcohol involvement is positively associated with total fatal crash rates across states. While alcohol is not the only factor influencing crash outcomes, it remains a significant behavioral risk indicator.

This project demonstrates how exploratory data analysis can uncover meaningful relationships in real-world state-level crash data.
