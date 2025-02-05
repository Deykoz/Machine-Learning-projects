# Weather Prediction using RNN

This project focuses on predicting the **maximum temperature** (`temp_max`) based on historical weather data. We use a **Recurrent Neural Network (RNN)**, which is particularly suited for time series data as it can capture temporal dependencies over time. The goal is to predict the temperature for the next day based on past weather conditions.

## Dataset

The dataset consists of daily weather records, including various variables such as:
- Temperature
- Precipitation
- Wind Speed
- Temperature Minima (temp_min)

## Objective

The objective is to predict the next day's **maximum temperature** (`temp_max`) by learning from historical weather data. We explore key concepts of **time series forecasting**, **data preprocessing**, and **RNN architecture**, specifically focusing on **LSTM (Long Short-Term Memory)** networks.

## Techniques Used

- **Recurrent Neural Networks (RNN)**: The model architecture used to handle time series data.
- **LSTM Layers**: Special RNN architecture that helps capture long-term dependencies.
- **Regularization**: Techniques like **dropout** to reduce overfitting and improve generalization.
- **Optimizers**: Exploring different optimizers (e.g., **RMSprop**, **Nadam**) for better convergence.
- **Early Stopping**: Preventing overfitting by stopping training early based on validation loss.

## Results

- **Model 1**: Showed overfitting, with high performance on the training set but poor performance on the validation and test sets (indicated by increasing **RMSE** and **MAE** values).
- **Model 2**: Provided better generalization than Model 1, but still struggled with **RMSE** on validation and test sets.
- Both models indicated that there is room for improvement, especially in reducing overfitting and enhancing generalization to unseen data.

## Conclusion

While **Model 2** performed better in terms of generalization, both models showed limitations in their ability to handle overfitting. Several strategies could be explored to enhance the models further:
- **Increasing LSTM complexity** (more units or layers).
- **Increasing the number of epochs** with **early stopping** to avoid overfitting.
- **Adjusting dropout rates** and experimenting with **BatchNormalization**.
- Exploring other optimizers such as **RMSprop** or **Nadam**.
- Investigating **data augmentation** or more advanced **feature engineering** techniques.

Due to time constraints, these approaches were not fully tested, but they provide promising avenues for improving model performance.

## Next Steps

- **Enhance LSTM Architecture**: Increase the number of LSTM units and layers.
- **Adjust Regularization**: Tune the dropout rate and implement BatchNormalization.
- **Optimizers**: Experiment with different optimizers (e.g., RMSprop, Nadam).
- **Feature Engineering**: Investigate more advanced techniques for data preprocessing and augmentation.
- **Cross-validation**: Implement cross-validation to better assess model performance.

## Notebook

You can find the notebook for this project here: [RNN_weather_prediction.ipynb](RNN_weather_prediction.ipynb)

