# Multiple Classification Models

This project aims to classify the severity of Obstructive Sleep Apnea (OSA) into three categories: **Healthy**, **Moderate**, and **Severe**. The classification is based on features such as **Age**, **BMI**, and **Cervical Circumference**.

## Dataset

The dataset used is provided by **Quirón Hospital of Málaga**, containing patient data relevant to OSA.

## Objective

The goal of this project is to compare the performance of various classification models (e.g., Logistic Regression, Random Forest, SVM, KNN) to determine which one provides the most accurate prediction of OSA severity.

## Techniques Used

- **Logistic Regression**
- **Ridge Classifier**
- **Random Forest**
- **Support Vector Machines (SVM)**
- **K-Nearest Neighbors (KNN)**
- **Gradient Boosting**
- **Bagged Decision Trees (Bagging)**

## Results

- Accuracy ranging from **0.43 to 0.55**.
- **Gradient Boosting** showed the best performance with an accuracy of **0.555**.
- Key challenges included **class imbalance** and **non-linearity** in the data.

## Next Steps

- Apply **class balancing** techniques like **SMOTE**.
- Further **hyperparameter tuning**.
- Explore **feature transformations** to improve model performance.

## Notebook

You can find the notebook for this project here: [Multiple_Classification_Models.ipynb](Multiple_Classification_Models.ipynb)

