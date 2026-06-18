#  Real Estate Valuation: Machine Learning Pipeline

## 📌 Project Overview
This repository contains an end-to-end Machine Learning pipeline developed to predict housing prices. The project goes beyond basic predictive modeling by incorporating domain-specific feature engineering, rigorous multicollinearity handling, and Explainable AI (XAI) to derive actionable business insights for real estate stakeholders.

## 🚀 Technical Highlights
* **Advanced EDA:** Conducted distribution analysis and utilized Variance Inflation Factor (VIF) to identify and mitigate inherent real estate multicollinearity.
* **Strategic Feature Engineering:** Synthesized raw binary features into a comprehensive `premium_amenities_score`, successfully capturing the "value multiplier" effect of bundled luxury features.
* **Model Benchmarking:** Evaluated a baseline Linear Regression model against a robust Random Forest Regressor, capturing complex non-linear relationships with an R² of ~0.62.
* **Explainable AI (XAI):** Integrated **SHAP (SHapley Additive exPlanations)** to mathematically quantify the exact financial impact of specific property features, transforming the model into transparent, stakeholder-ready insights.

## 📂 Repository Structure
```text
HousePricePrediction_AasthaMalviya/
├── analysis.ipynb           # Complete Colab Notebook containing EDA, ML pipeline, and XAI
├── Housing.csv              # The core dataset
├── summary.pdf              # 1-page executive summary and business recommendations
└── charts/
    ├── Chart1_Price_Distribution.png       # Target variable skewness analysis
    ├── Chart2_Correlation_Heatmap.png      # Feature relationship matrix
    └── Chart3_SHAP_Feature_Importance.png  # Mathematical breakdown of feature impact
