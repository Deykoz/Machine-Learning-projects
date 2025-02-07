# Machine Learning Projects

Welcome to my collection of Machine Learning projects! This repository contains various projects where I apply different machine learning techniques to real-world problems. Each project has its own folder with detailed descriptions, datasets, and notebooks.

## Projects

Here is a list of the projects included in this repository:

### 1. **[Weather Prediction using RNN](./Weather%20Prediction%20using%20RNN)**
   - **Description**: In this project, we predict the **maximum temperature** (`temp_max`) based on historical weather data, including variables like temperature, precipitation, wind speed, and minimum temperature. The goal is to create an accurate weather forecasting model using a **Recurrent Neural Network (RNN)**, which is effective for time series prediction due to its ability to capture temporal dependencies.
   - **Dataset**: Daily weather records of Seatle found on Kaggle (temperature, precipitation, wind speed, etc.).
   - **Objective**: The objective is to predict the next day's maximum temperature using an RNN trained on historical weather data.
   - **Results**: Model 2 achieved better generalization than Model 1, but both models still showed overfitting and need improvements. Techniques like adjusting LSTM units, dropout rates, and adding more layers could improve the model.
   - **Next Steps**: Explore strategies such as **increasing the number of LSTM units**, **adjusting dropout rates**, and **experimenting with different optimizers** for better convergence.

### 2. **[CNN for Image Classification (CIFAR-10)](./CNN%20for%20classification%20of%20image)**
   - **Description**: Build a **Convolutional Neural Network (CNN)** for classifying images from the **CIFAR-10 dataset**, which contains 60,000 images across 10 classes (e.g., airplanes, cars, animals). The focus is on understanding deep learning fundamentals such as **convolutional layers**, **pooling**, and **activation functions**.
   - **Dataset**: **CIFAR-10** dataset.
   - **Results**: The model achieved an accuracy of **75.8%**, with the best performance coming from optimizing **convolutional layers**, **batch size**, and using **LeakyReLU** activation.
   - **Next Steps**: Explore techniques like **data augmentation**, **transfer learning**, and further hyperparameter tuning.
     
### 3. **[Multiple_Classification_Models](./Multiple_Classification_Models)**
   - **Description**: Classify the severity of **Obstructive Sleep Apnea (OSA)** into three categories: Healthy, Moderate, and Severe, using classification models like **Logistic Regression**, **Random Forest**, **SVM**, and **KNN**. The goal is to determine which model gives the most accurate predictions.
   - **Dataset**: Provided by **Quirón Hospital of Málaga**.
   - **Results**: The best performance was achieved with **Gradient Boosting**, with an accuracy of **0.555**. 
   - **Next Steps**: Apply techniques like **SMOTE**, feature transformations, and hyperparameter tuning.

### 4. **[Multiple Regression Models](./Multiple_Regression_Models)**
   - **Description**: In this project, we aim to predict the **Apnea-Hypopnea Index (IAH)** using features like **Age**, **BMI**, and **Cervical**. We evaluate the performance of various regression models, including both linear and non-linear approaches, to determine the most accurate model for IAH prediction.
   - **Models Used**: Linear Regression, Ridge Regression, Lasso Regression, Elastic Net Regression, Polynomial Regression, Random Forest Regression.
   - **Results**: **Polynomial Regression** performed the best with an **R²** of **0.2707**, while **Random Forest** showed poor performance, likely due to overfitting. The linear models (Linear, Ridge, Lasso, and Elastic Net) yielded similar results with **R²** around **0.25**.
   - **Next Steps**: Investigate alternative ensemble methods for better performance, and explore hyperparameter tuning for the Random Forest model.

Feel free to explore each project to understand the algorithms and techniques I used, along with any insights or challenges I encountered.
