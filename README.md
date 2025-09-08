# ESG Perk Preference Survey Report

This project analyzes contributor preferences for **ESG-related perks** using survey data (N=67). The goal is to identify demographic and experiential factors that influence perk choices and provide insights for designing engagement strategies.

## Overview
Perk structures can shape contributor motivation and participation in ESG initiatives. By combining **descriptive statistics**, **chi-square tests**, and **multinomial logistic regression**, this project evaluates how age, gender, education, occupation, income, and ESG program experience relate to perk preferences.

## Data
- **Respondents:** 67  
- **Demographics:**  
  - Age groups: 20s (20), 30s (15), 40s (15), 50s (10), 60+ (7)  
  - Gender: Female (33), Male (32), Non-binary (2)  
  - Education: High school (15), Undergraduate (30), Graduate (22)  
- **ESG-related occupation:** Yes (26), No (41)  
- **ESG program experience:** Yes (30), No (37)  
- **Perk preference categories:**  
  - Financial reward (26)  
  - Experience-based reward (25)  
  - Eco-friendly reward (10)  
  - Social contribution reward (6)  

## Methods
1. **Exploratory Data Analysis (EDA)**  
   - Frequency distributions and cross-tabulations of perk preferences by demographic groups.  

2. **Chi-square Tests**  
   - Tested independence between perk preference and categorical predictors (age, gender, education, ESG interest).  

3. **Multinomial Logistic Regression**  
   - Financial reward set as reference category.  
   - Predictors: age, gender, education, income, ESG occupation, ESG program experience, ESG interest.  
   - Results reported as odds ratios (OR) with p-values.  

## Results
- **Exploratory Findings:**  
  - Younger respondents (20s–30s) preferred experience-based rewards.  
  - Older respondents (40+) leaned toward financial rewards.  
  - Gender and education differences were modest.  

- **Chi-square Tests:**  
  - No statistically significant associations (p > 0.05).  

- **Multinomial Logistic Regression:**  
  - **Age (20s–30s):** Higher odds of preferring experience-based rewards over financial (OR ≈ 4.3, p = 0.039).  
  - **ESG program experience:** Associated with lower odds of preferring experience-based rewards (p = 0.047).  
  - Other predictors were not significant.  

## Key Insights
- Financial and experience-based rewards dominate overall preferences.  
- Younger respondents are more motivated by **experiences**, while older respondents prefer **financial incentives**.  
- ESG program experience unexpectedly reduced preference for experience-based perks.  
- A **flexible mix of financial and experiential rewards**, complemented by eco-friendly and social contribution options, can maximize engagement while aligning with ESG values.

---
