# natural_disaster_MLproject
Predicting disaster damage and detecting anomalies for better disaster risk planning.

---

# Disaster Damage Prediction & Anomaly Detection

This project focuses on predicting the economic impact of natural disasters and detecting unusual disaster events using machine learning and real-world data. By leveraging models like XGBoost and HDBSCAN, it combines predictive analytics with anomaly detection to support disaster response planning, resource allocation, and resilience assessment.

## Overview

Using real-world disaster data, this project:

* Predicts total economic damage from disasters using tree-based models (XGBoost, CatBoost)
* Identifies key predictors such as coping capacity, disaster type, and total deaths
* Detects anomalous disaster events using unsupervised clustering (HDBSCAN)
* Highlights high-impact countries and events to support decision-making in disaster response and planning

## Key Features

* Machine learning model to predict disaster damage (R² ≈ 0.83)
* Anomaly detection to flag underreported or extreme events
* Visualizations of top anomalies and global disaster impact
* Integration of INFORM risk index for contextual vulnerability

## Tools & Technologies

* Python (Pandas, Scikit-learn, XGBoost, CatBoost, HDBSCAN)
* Plotly & Matplotlib for visualization
* Jupyter Notebooks for experimentation and reporting

## Use Cases

* Support early disaster damage estimation and aid prioritization
* Inform policy on disaster preparedness and climate adaptation
* Assist NGOs and governments in resource allocation
* Guide infrastructure planning and risk assessment

## Future Improvements

* Integrate real-time weather or spatial data
* Expand to include smaller-scale disasters
* Explore time-series models for temporal forecasting

-------------------

Included Files

Jupyter Notebook with all code, preprocessing steps, model training, evaluation, and plots.

Original Datasets:

  * `public_emdat_2025-05-12.xlsx`
  * `inform_risk_mid_2024_v068.xlsx`
  * `Population_Density__Long_Format_WB.csv`
  * `GDP_per_Capita__Long_Format_.csv`
  * `Our_World_In_Data_v7_2022.csv`

Cleaned Dataset: Combined and preprocessed version used for modeling.

Summary slides with methodology, results, and visualizations.

Instructions to Run the Analysis:

1. Clone or download the repository.
2. Make sure you have Python 3.8 or higher.
3. Install the required Python libraries:

```
pip install pandas numpy scikit-learn matplotlib seaborn xgboost catboost lightgbm hdbscan plotly
```

4. Open and run the `Disaster_Impact_Analysis.ipynb` notebook in Jupyter or Google Colab.
5. Follow the notebook cells sequentially to:

   * Load and clean data
   * Train models
   * Evaluate results
   * Visualize anomalies and feature importance


Acknowledgments
Some components of this project were refined with guidance from OpenAI's ChatGPT, including:
* Implementation of CatBoost for damage prediction
* Initial setup and structure of the neural network model (MLPRegressor)
* Integration of HDBSCAN for anomaly detection
ChatGPT support contributed to improving the code quality, model structure, and workflow.


