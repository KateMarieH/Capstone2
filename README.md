# California School Dashboard Prediction Project

## Overview
This project analyzes multiple years of California School Dashboard data for Aspire Public Schools and builds a predictive model to forecast **next year’s Dashboard performance color** for each school, indicator, and student group. The Dashboard assigns performance levels (Red, Orange, Yellow, Green, Blue) across several state indicators, and predicting these levels helps identify trends, equity gaps, and areas needing support.

The project includes:
- Raw Dashboard text files (tab-delimited)
- Data wrangling and cleaning
- Exploratory data analysis (EDA)
- Predictive modeling
- Final results and visualizations

---

## Project Goal
To develop a machine learning model that predicts **next-year Dashboard color** using:
- Prior-year Dashboard color  
- Change level  
- Indicator type  
- Student group characteristics  
- School-level demographics  
- Multi-year historical patterns  

This is framed as a **multiclass classification** problem.

---

## Dashboard Indicators Included
This project uses the following **State Indicators**:

- English Language Arts (ELA) Academic Indicator  
- Mathematics Academic Indicator  
- Chronic Absenteeism Indicator  
- College/Career Indicator (CCI)  
- English Learner Progress Indicator (ELPI)  
- Graduation Rate Indicator  
- Science Indicator  
- Suspension Rate Indicator  

Local Indicators are excluded because they do not produce performance colors and are not suitable for predictive modeling.

---

## Repository Structure
capstone-2/
│
├── data/
│   ├── raw/                # Raw Dashboard .txt files by year
│   └── processed/          # Cleaned and combined dataset
│
├── notebooks/
│   ├── 01_data_wrangling.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_modeling.ipynb
│   └── 04_results_and_visuals.ipynb
│
├── src/
│   ├── load_data.py
│   ├── clean_data.py
│   ├── feature_engineering.py
│   └── modeling.py
│
├── reports/
│   ├── figures/
│   └── final_report.md
│
├── README.md
└── .gitignore

---

## Data Sources
All data comes from the **California School Dashboard** public releases.  
Files are downloaded as tab-delimited `.txt` files and stored in `data/raw/`.

Years included:
- 2017  
- 2018  
- 2019  
- (COVID gap: 2020–2021)  
- 2022  
- 2023  
- 2024  

Each file includes:
- School name and CDS code  
- Student group  
- Indicator type  
- Status (numeric score)  
- Performance level (color)  
- Change level  
- Additional demographic and context fields  


