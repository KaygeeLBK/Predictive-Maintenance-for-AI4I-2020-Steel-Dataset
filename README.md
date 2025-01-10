# Predictive Maintenance for AI4I 2020 Steel Dataset

## Overview
This project focuses on implementing a predictive maintenance model using the AI4I 2020 Steel Dataset. Predictive maintenance is a proactive maintenance strategy that leverages data analytics and machine learning to predict equipment failures before they occur. This approach reduces downtime, minimizes maintenance costs, and extends the lifespan of machinery, making it essential for industries reliant on continuous operation, such as manufacturing and steel production.

## Problem Statement
In industrial environments, unexpected machine failures can result in significant production downtime, safety hazards, and financial losses. Traditional maintenance strategies, such as reactive and preventive maintenance, are either too late or too frequent, leading to inefficiencies. This project aims to build a robust machine learning model to accurately predict machine failures based on sensor data and operational parameters, allowing for timely and effective maintenance interventions.

## Dataset
- **Dataset:** AI4I 2020 Predictive Maintenance Dataset  
- **Source:** UCI Machine Learning Repository  
- **Features:**
  - Air temperature
  - Process temperature
  - Rotational speed
  - Torque
  - Tool wear
  - Product type (categorical)
- **Targets:**
  - Machine failure (binary)
  - Five specific failure modes: TWF, HDF, PWF, OSF, RNF

## Tools and Technologies Used
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow, Keras, Keras Tuner, SMOTE (imbalanced-learn)

## Model Development
- **Model:** Fully Connected Neural Network (FNN)  
- **Optimization:** Hyperparameter tuning with Keras Tuner (layers, dropout rate, learning rate)  
- **Data Balancing:** Applied SMOTE to address class imbalance in failure prediction  
- **Loss Function:** Binary Cross-Entropy  
- **Optimizer:** Adam  

## Results
- **Validation Accuracy:** 95%  
- **F1-Score:** 0.93  
- **Confusion Matrix:** Demonstrated high precision and recall for machine failure prediction

## Conclusion
The implemented model successfully predicts machine failures with high accuracy, enabling effective predictive maintenance in industrial settings. This approach minimizes downtime, reduces maintenance costs, and improves operational efficiency.

## Future Work
- Explore advanced models (e.g., LSTM, Random Forest) for time-series data.
- Integrate real-time monitoring systems for live predictions.
- Implement cost-sensitive learning to prioritize critical failures.


**Author:** Kagiso Leboka 
**Date:** 20/12/2024


