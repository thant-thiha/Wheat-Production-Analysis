# Wheat Production Predictive Analytics

**Goal:** Analyze and optimize wheat production and supply chain efficiency using data-driven methods.

## Overview
This project analyzes global wheat production using a real-world agricultural dataset and machine learning, following the PACE (Plan–Analyze–Construct–Execute) framework. The primary aim is to identify key factors driving wheat yield and optimize supply chain and pricing strategies across six continents

## Dataset
- 890 records × 9 fields: region, weather, soil, fertilizer, pest, cost, price, yield, farmer satisfaction
- Data sourced from multinational company operations in Brazil, India, Australia, USA, Canada, Syria
- Minimal missing data; columns renamed for clarity

## Approach
- **Data Cleaning/EDA:** Validated and cleaned production, weather, soil, cost, and yield data.
- **Feature Engineering:** Created metrics such as fertilizer efficiency, ROI, profit per hectare.
- **Statistical Analysis:** Explored regional, soil, and weather impacts on yield and profit.
- **Modeling:** Compared PCA, LDA for dimensionality reduction, and built classification/regression models (Random Forest, XGBoost, Logistic Regression).
- **Evaluation:** Assessed model performance, feature importance, and provided improvement strategies.

## Key Insights
- **Top yield/profit:** North America, Asia, Africa highest ROI and net yield; price, fertilizer, pest, and cost key predictors.
- PCA and LDA show limited class separation, highlighting the complexity of predicting yield bins
- **Low model accuracy:** Predicting yield category is complex; current features need improvement for stronger prediction.
- **Practical recommendations:** Enhance features, expand sample diversity, tune hyperparameters, and target process improvements for robust, data-backed decisions.

## Limitations & Recommendations
- Features lack strong predictive power: improved sampling and additional data (remote sensing, phenological) advised
- Advanced feature selection, normalization, and robust cross-validation can enhance generalization

## Resources
- [Full Report](https://github.com/thant-thiha/Wheat-Production-Analysis/blob/main/Wheat-Production-Predictive-Analytics.pdf)
- [Analysis Notebook](https://github.com/thant-thiha/Wheat-Production-Analysis/blob/main/Wheat-Production-Analysis.ipynb)
