# Predictive-Maintenance-CCE2
Predictive Maintenance for Computer Laboratory Equipment using K-Means and Decision Tree.

Predictive Maintenance for Computer Laboratory Equipment

Case Study – CCE-2

1. Introduction

Predictive maintenance uses data analysis and machine learning techniques to identify equipment that may require maintenance. This case study focuses on predicting maintenance risk for computer laboratory equipment using usage hours, temperature, fault records, and equipment age.

2. Problem Statement

A college maintains computers, printers, and networking devices. The objective is to analyze maintenance logs, usage hours, temperature readings, and fault records. Clustering is used to identify equipment behavior patterns, while classification predicts predefined maintenance-risk categories.

3. Objectives

- Analyze computer laboratory equipment data.
- Identify equipment behavior patterns using clustering.
- Predict maintenance-risk categories using classification.
- Evaluate model performance using suitable metrics.
- Support maintenance planning and reduce unexpected equipment failures.

4. Dataset Description

The dataset contains 200 sample records with the following features:

- Equipment ID
- Equipment Type
- Usage Hours
- Temperature
- Fault Count
- Equipment Age
- Maintenance Risk

Note: The dataset is synthetically generated for this academic case study.

5. Technologies Used

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

6. Methodology

1. Generate and load the equipment dataset.
2. Preprocess the data and select relevant features.
3. Apply K-Means clustering to identify equipment behavior patterns.
4. Train a Decision Tree classifier to predict maintenance-risk categories.
5. Evaluate the classification model using accuracy, classification report, and confusion matrix.
6. Save the results, visualizations, and trained models.

7. Results and Evaluation

The case study generates equipment clusters and evaluates the Decision Tree classification model. The results and confusion matrix are included in the repository for analysis.

The findings are intended to demonstrate how machine learning can support maintenance planning. Since the dataset is synthetic, the results should not be treated as validated real-world performance.

8. Repository Contents

- "Predictive_Maintenance_CCE2.ipynb" – Jupyter Notebook containing the implementation.
- "equipment_data.csv" – Sample equipment dataset.
- "equipment_results.csv" – Output results, if included.
- "kmeans_clusters.png" – Clustering visualization, if included.
- "confusion_matrix.png" – Classification evaluation visualization, if included.
- Model files (".pkl") – Saved trained models and scaler, if included.

9. Conclusion

This case study demonstrates the application of clustering and classification techniques to predictive maintenance for computer laboratory equipment. It provides an academic example of how data-driven methods can help identify maintenance risks and support maintenance decisions.

10. Academic Purpose

This project is prepared as part of the CCE-2 case study for academic learning and evaluation.
