# City Taxi Trip Duration Prediction

This project focuses on predicting the duration of city taxi trips using machine learning techniques. The dataset used in this project consists of taxi trip records provided by the NYC Taxi and Limousine Commission (TLC). The goal is to build a model that accurately estimates the trip duration based on various features such as pickup and drop-off dates/times, locations, distances, and additional trip details.

The dataset has been preprocessed to handle missing values, perform exploratory data analysis, and create relevant features for modeling purposes.

# Methodology

The project follows the following steps:

Data Cleaning: Any missing values are removed from the dataset to ensure data integrity.

Missing Value Analysis: The presence of missing values is analyzed and handled appropriately.

Exploratory Data Analysis: The dataset is explored to gain insights into the data distribution, relationships between variables, and potential patterns.

Feature Creation: Additional features are derived from existing variables to enhance the model's predictive capability.

Model Building: A linear regression model is trained using the preprocessed dataset to predict the taxi trip duration.

Evaluation: The trained model is evaluated using common regression evaluation metrics such as mean squared error (MSE) and mean absolute error (MAE).

Prediction: The trained model is used to predict the duration of taxi trips in the test dataset.

Deployment: The predicted results are saved and can be further utilized or analyzed as needed.

# Requirements

To run the project code, the following libraries are required:

pandas,
numpy,
scikit-learn,
matplotlib

# Usage

1. Clone the repository.
2. Download the train and test datasets from the provided source and place them in the repository folder.
3. Run the Python code to perform data cleaning, feature creation, model training, evaluation, and prediction.
4. View the evaluation metrics and the predicted results for the test dataset.
5. Further analyze or utilize the predicted results as per your requirements.


