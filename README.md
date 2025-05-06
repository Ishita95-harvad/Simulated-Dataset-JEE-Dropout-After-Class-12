# Simulated-Dataset-JEE-Dropout-After-Class-12
Simulated Dataset: JEE Dropout After Class 12
# JEE Dropout Prediction

This project aims to predict student dropouts after class 12 based on various factors, including exam scores, study habits, and mental health. The notebook provides a machine learning model trained on a simulated dataset to identify potential dropouts.

## Installation
python !pip install pandas==1.5.3 !pip install scikit-learn==1.2.2
## Usage
python

Load the dataset
data = pd.read_csv('jee_dropout_data.csv')

Preprocess the data
...
Train the model
model = LogisticRegression() model.fit(X_train, y_train)

Make predictions
predictions = model.predict(X_test)

## Data Source

The dataset used in this project is a simulated dataset generated for demonstration purposes. You can find the dataset within the notebook's files.

## License

This project is licensed under the Apache License 2.0.

## Contact

For any questions or feedback, please contact at Email Id-bahamniaishita@gmail.com.
