# California School Dashboard Prediction Project

## Overview
This project analyzes multiple years of California School Dashboard data for Aspire Public Schools and builds a predictive model to forecast **next year’s Dashboard performance color** for each school and Dashboard Indicator. The Dashboard assigns performance levels (Red, Orange, Yellow, Green, Blue) across several state indicators, and predicting these levels helps identify trends, equity gaps, and areas needing support.

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
  


---

## Dashboard Indicators Included
This project uses the following **State Indicators**:

- English Language Arts (ELA) Academic Indicator  
- Mathematics Academic Indicator  
- Chronic Absenteeism Indicator  
- Suspension Rate Indicator  


---

## Data Sources
All data comes from the **California School Dashboard** public releases.  
Files are downloaded as tab-delimited `.txt` files and stored in `data/raw/`.

Years included:
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



