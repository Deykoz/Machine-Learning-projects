# Machine Learning Projects

Welcome to my collection of Machine Learning projects! This repository contains various projects and experiments where I applied different machine learning algorithms and techniques. Below you will find a list of the projects included, along with a brief description of each.

## Projects

### 1. **Multiple_Classification_Models.ipynb**
   - **Description**: In this project, we aim to classify individuals based on the severity of Obstructive Sleep Apnea (OSA) using several classification models. The goal is to predict the severity level of OSA, categorized into three classes according to the Apnea-Hypopnea Index (AHI):
     - **Healthy OSA** (IAH <= 10)
     - **Moderate OSA** (IAH >10 and IAH <30)
     - **Severe OSA** (IAH >= 30)
   - **Features**: Age, BMI, and Cervical.
   - **Dataset**: The dataset used for this analysis was provided by the Quirón Hospital of Málaga. It contains data from patients who were analyzed using Polysomnography after OSA was suspected.
   - **Objective**: The objective of the project is to compare the performance of various classification models and determine which one provides the most accurate prediction of OSA severity.
   - **Techniques Used**: Logistic Regression, Random Forest, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), and more.
   - **Results**: The analysis of the eight classification models highlights overall modest performance, with accuracies ranging between **0.43 and 0.55**, reflecting significant challenges related to data complexity and class imbalance. 
     
     - **Gradient Boosting** emerged as the top performer, achieving the highest overall accuracy (**0.555**) and relatively balanced performance across classes.
     - **Linear models** such as Logistic Regression and Ridge Classifier struggled with the non-linearity of the data.
     - The "Severe" and "Moderate" classes proved particularly challenging, with consistently low recall across most models.

     To improve performance, we could try:
     - Applying **class balancing techniques** (e.g., SMOTE, class weighting).
     - Exploring **feature transformations** to better capture non-linearity.
     - Fine-tuning hyperparameters for complex models like **Random Forest** and **Gradient Boosting**.
     - Using **weighted metrics** to provide a fairer evaluation in this highly imbalanced context..
   -  **Notebook/Code**: [Multiple_Classification_Models.ipynb](./Multiple_Classification_Models.ipynb)



