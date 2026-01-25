# YBI-Foundation
## Anomaly Detection in Industrial Cyclone Sensor Data

# Project Overview
This project focuses on detecting abnormal operating conditions in industrial cyclone equipment using unsupervised machine learning algorithms.
Sensor data collected at regular time intervals is analyzed to identify deviations from normal behavior, which may indicate potential equipment faults or process issues.

# Problem Statement
To detect anomalies in industrial cyclone sensor data by learning normal operating patterns and identifying unusual behavior without using labeled data.

# Dataset Description
The dataset contains time-series sensor readings recorded every few minutes from cyclone equipment.

# Sensor Features Used:
1) Inlet Gas Temperature (°C)
2) Material Temperature (°C)
3) Outlet Gas Draft (Pressure)
4) Cone Draft (Pressure)
5) Gas Outlet Temperature (°C)
6) Inlet Draft (Pressure)

# Machine Learning Algorithms Used :-
# Isolation Forest 
– Detects global anomalies by isolating rare observations
# Local Outlier Factor (LOF) 
– Identifies local density-based anomalies
# K-Means Clustering 
– Flags points far from cluster centers as anomalies
# A majority voting approach is used to produce the final anomaly decision.

# Project Workflow

1) Load and preprocess sensor data
2) Apply feature scaling
3) Train multiple unsupervised ML models
4) Detect anomalies from each model
5) Combine results for robust anomaly detection
6) Visualize detected anomalies

# Technologies Used :-
1) Python
2) Pandas, NumPy
3) Scikit-learn
4) Matplotlib

# Output
Binary anomaly labels for each data point.
Final anomaly flag based on multiple models.
Visual representation of anomalies over time.


##  How to Run the Project

###  Clone the Repository
git clone https://github.com/SoorajBhat29/YBI-Foundation.git

