

# Industrial Anomaly Detection with Isolation Forest:
This project is a machine learning solution designed to automatically detect operational anomalies in multivariate time series data from industrial sensors. The core of the system is the Isolation Forest algorithm, an efficient, unsupervised method for identifying outliers.

## Core Functionality
Unsupervised Learning: It uses the Isolation Forest algorithm to learn the patterns of normal behavior from a baseline period without needing pre-labeled data.

Anomaly Scoring: The system analyzes the entire dataset, assigning a 0-100 anomaly score to each timestamp to quantify unusual behavior.

Root-Cause Analysis: For severe anomalies, the system pinpoints the specific features (sensor readings) that deviated most significantly from the norm, providing actionable insights for maintenance and monitoring.

## Technologies Used
Python

Pandas

Scikit-learn (for the `IsolationForest` implementation)

NumPy
