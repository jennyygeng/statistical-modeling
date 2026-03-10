# Tucson Housing Price Prediction 🏡📈

A statistical modeling project that predicts housing prices in Tucson, Arizona, using multiple linear regression and backward stepwise feature selection.

## 📌 Project Overview
While many predictive modeling projects rely on pre-cleaned, standardized datasets, this analysis utilizes raw public sales and property characteristic data sourced directly from the Pima County Assessor's Office. The objective was to build a robust statistical model to identify the most significant drivers of property value.

## 🔬 Statistical Methodology
* **Data Engineering:** Cleaned and merged disparate Assessor datasets using R's `tidyverse`, handling missing values, and formatting mixed data types for modeling.
* **Model Selection:** Implemented backward stepwise selection to iteratively refine a multiple linear regression model.
* **Feature Optimization:** Utilized the Akaike Information Criterion (AIC) to evaluate model quality, successfully balancing goodness-of-fit against complexity to prevent overfitting.
* **Performance:** The final optimized model successfully isolates 8 key statistically significant predictors (e.g., square footage, year built, bathroom fixtures) from the raw data.

## 🛠️ Tech Stack
* **Language:** R
* **Libraries:** `tidyverse`, `stats`
* **Environment:** R Markdown

## 📂 Repository Contents
* **`Midterm Project.Rmd`**: The R script containing the data cleaning pipeline, regression modeling, and AIC selection process.
* **`DATA 467 Midterm Project.pdf`**: The final abstract and technical report detailing the mathematical findings and model summary.
