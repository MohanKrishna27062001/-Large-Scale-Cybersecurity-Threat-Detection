# -Large-Scale-Cybersecurity-Threat-Detection

Large-Scale Cybersecurity Threat Detection Using Machine Learning:
This project presents a scalable and high-performance Intrusion Detection System (IDS) using machine learning models implemented in PySpark. The system is built to detect a wide range of cyberattacks in real-time using the UNSW-NB15 dataset. We also integrated Quantum Machine Learning (QML) to improve accuracy on zero-day and complex threats.

Project Objectives:
Detect various types of cyber threats from network traffic data using ML.
Achieve high accuracy and low false positives for real-time IDS.
Leverage distributed computing (PySpark) for large-scale scalability.
Integrate Quantum Machine Learning for advanced threat detection.
Reduce model training time via dimensionality reduction techniques.

Technologies Used:
Python, PySpark, Jupyter Notebook
Machine Learning Models: Decision Tree, Naïve Bayes, Random Forest, Gradient Boosting
Dimensionality Reduction: Principal Component Analysis (PCA)
Unsupervised Learning: K-Means Clustering
Quantum ML: Hybrid classification model using QML principles
Libraries: scikit-learn, pandas, seaborn, matplotlib, pyspark.ml, qiskit (if applicable)

Dataset:
UNSW-NB15 Dataset by Australian Centre for Cyber Security
2.5+ million labeled network flows
49 features (basic, content-based, time-based, connection-based)
9 attack categories including DoS, exploits, fuzzers, reconnaissance, worms, and more

Key Results:
Metric	Value
Accuracy	~98%
Precision	0.97
Recall	0.98
F1-Score	0.97
ROC-AUC	0.99
Feature Reduction	49 → 25 features (via PCA)
Training Time Reduction	~40%
Computation Time Reduction	~80% (with PySpark)


Methodology:

Data Preprocessing:
Missing value handling, one-hot encoding, feature normalization
Feature Selection:
PCA and feature importance ranking
Model Training (Distributed via PySpark):
Decision Tree, Random Forest, Naïve Bayes, Gradient Boosting
Evaluation:
Accuracy, Precision, Recall, F1, ROC-AUC
Unsupervised Pattern Discovery:
K-means clustering for behavior grouping
Quantum Machine Learning (QML):
Hybrid QML integration to detect zero-day threats

