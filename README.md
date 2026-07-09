# Insurance Charges Prediction using ANN

## Objective
The objective of this project is to predict insurance charges using an Artificial Neural Network (ANN).

## Dataset
insurance.csv

## Steps Performed
- Loaded the dataset using Pandas.
- Explored the dataset using info(), describe(), and checked for missing values.
- Encoded categorical variables using LabelEncoder.
- Split the dataset into training and testing sets.
- Standardized the feature values using StandardScaler.
- Built an ANN model using TensorFlow/Keras.
- Compiled and trained the model using Adam optimizer and Mean Squared Error loss.
- Evaluated the model using MAE, MSE, RMSE, and R² Score.
- Saved the trained model and prediction results.

## Observation
The ANN model successfully learned the relationship between input features and insurance charges. Feature scaling improved training performance, and the model achieved good prediction accuracy on the test dataset.
