# Weather-Prediction
This documentation provides a detailed guide on the development and usage of a weather prediction machine learning model using Random Forests. The model is designed to predict temperature based on historical weather data, leveraging the Random Forest algorithm for its robustness and accuracy in handling various data types and complexities. The goal is to create a reliable tool for short-term weather forecasting that can be used for research, educational purposes, or practical applications in meteorology.

# Requirements
Python 3.7+
pandas
numpy
scikit-learn
matplotlib
seaborn

#Approach
The data was prepared, checked for any missing values or outliers and transformed into a suitable format for model training.
Then the dataset is split into training and testing sets to evaluate the model's performance on unseen data, ensuring that the model can generalize well to new data.
The Random Forest model is trained on the training set using the historical weather data. The model parameters are tuned to achieve the best performance, leveraging the ensemble nature of Random Forests to improve accuracy and reduce overfitting.
The trained model makes predictions on the test set to assess its performance. These predictions are then compared to the actual values to measure accuracy.
The model is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) to gauge its accuracy and reliability. These metrics provide insight into how closely the model's predictions match the actual values.
