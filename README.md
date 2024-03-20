# Iris Species Classification Project

This project aims to classify iris flowers into different species using the Support Vector Classifier (SVC) model. The dataset used for this classification task is the famous Iris dataset, which contains measurements of various iris flowers' features.

## Dataset
The dataset contains the following columns:
- SepalLengthCm: Length of the sepal in centimeters.
- SepalWidthCm: Width of the sepal in centimeters.
- PetalLengthCm: Length of the petal in centimeters.
- PetalWidthCm: Width of the petal in centimeters.
- Species: Species of the iris flower.

## Workflow
1. Load the dataset and preprocess it by dropping the 'Id' column.
2. Split the dataset into features (X) and target (y).
3. Split the data into training and testing sets using train_test_split.
4. Create an SVC model with gamma='scale' and fit it to the training data.
5. Make predictions on the test data.
6. Evaluate the model's performance using accuracy_score.
7. Visualize the decision boundaries using PCA for dimensionality reduction and scatter plot.

## File Structure
- `iris.csv`: The dataset file.
- `iris_classification.ipynb`: Jupyter Notebook containing the Python code for the project.
- `README.md`: This file.

## Usage
To run the code:
1. Clone the repository:
