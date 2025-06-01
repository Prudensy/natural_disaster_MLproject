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
