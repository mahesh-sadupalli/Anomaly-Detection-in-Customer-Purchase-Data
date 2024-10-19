# Anomaly-Detection-in-Customer-Purchase-Data


# Project Description
This project focuses on detecting and explaining anomalies in the UCI Wholesale Customers dataset using unsupervised machine learning techniques. The goal is to identify customers with abnormal spending behavior across various product categories and provide insights into what drives these anomalies.

# Technical Specifications
Programming Language: Python
Libraries:
NumPy (Data manipulation)
pandas (Data processing)
scikit-learn (Machine learning algorithms)
Matplotlib & Seaborn (Data visualization)
PyTorch/TensorFlow (For neural network-based models, if applicable)
Dataset: UCI Wholesale Customers Dataset, available here

# Project Goals

Data Preprocessing: Clean and prepare the dataset by handling missing values, transforming the data (e.g., log transformations), and ensuring consistency across features.
Anomaly Detection: Implement nearest-neighbor-based anomaly detection models, including improvements like softmin anomaly scoring, to ensure robustness.
Explainability: Use Layer-wise Relevance Propagation (LRP) techniques to explain why specific instances are considered anomalous, focusing on identifying key input features contributing to anomalies.

Results
Identified top 10 most anomalous wholesale customers based on their spending behavior.
Demonstrated robustness of the anomaly detection algorithm using softmin scoring to improve reproducibility.
Provided feature-level insights into the anomalies by identifying which spending categories (e.g., Fresh, Milk, Grocery) most significantly influenced the anomaly scores.
