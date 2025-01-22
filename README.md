# Predictive Maintenance for Wind Turbines

## Overview
This project focuses on developing a **predictive maintenance system** for wind turbines using **data-driven approaches**. By analyzing SCADA data and applying machine learning models, we aim to detect early signs of component failures, enabling proactive interventions and minimizing operational disruptions.

## Objectives
- Develop an **early warning system** to anticipate faults in key wind turbine components.
- Utilize **SCADA data** and advanced analytics to improve failure detection.
- Implement **machine learning models** to balance precision and minimize unnecessary maintenance.
- Provide insights to optimize maintenance schedules and enhance operational efficiency.

## Methodology
Our approach leverages data from turbine operations, including:
1. **Data Collection:** 
   - SCADA system data with key metrics (power output, temperature, vibrations).
   - Meteorological data for environmental context.
2. **Feature Engineering:** 
   - Dimensionality reduction using **Principal Component Analysis (PCA)**.
   - Rolling averages and lagged features to capture long-term trends.
3. **Modeling Techniques:**  
   - **Random Forest**, **XGBoost**, and **AdaBoost** for failure predictions.
   - **LSTM Networks** for capturing sequential dependencies.
   - **CUSUM Anomaly Detection** for unsupervised pattern identification.
4. **Evaluation Metrics:**
   - Fréchet Inception Distance (FID) for model accuracy.
   - Precision, recall, and F1-score for failure detection performance.

## Results
- The implemented models successfully predicted turbine failures with significant lead times.
- The **Random Forest model** performed best overall, providing reliable failure warnings.
- Anomaly detection techniques highlighted critical patterns preceding failures.

## Challenges
- Handling noisy and imbalanced data in SCADA logs.
- Reducing false positives while maintaining early detection capabilities.
- Optimizing computational efficiency for real-time monitoring.

## Future Improvements
- Exploring deep learning models for enhanced predictive accuracy.
- Incorporating additional environmental factors for better failure predictions.
- Deploying the system in a real-time operational environment.

## Project Report
For detailed analysis, experimental results, and insights, refer to the **[Project Report](./CDA_Project_Report.pdf)**.

## Code Availability
The project code is **not available for public visibility**, but the report contains all relevant details regarding methodology and results.

