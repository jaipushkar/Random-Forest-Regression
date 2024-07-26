# Random-Forest-Regression

**Digits Recognition using Random Forest Classifier**
This project involves recognizing handwritten digits (0-9) using the Digits dataset and the Random Forest classifier.

**Dataset**
The Digits dataset is loaded from the sklearn.datasets module. It includes:
8x8 pixel images of handwritten digits (0-9)
A target variable indicating the digit

**Steps**
**Data Loading and Preparation:**
Loaded the Digits dataset.
Created a DataFrame from the dataset, including both the image data and the target labels.

**Model Training:**
Split the dataset into training and testing sets, with 20% of the data used for testing.
Trained a Random Forest classifier using the training set.

**Model Evaluation:**
Evaluated the model's accuracy on the testing set.
Used the trained model to predict the digits in the testing set.

**Dependencies**
pandas
scikit-learn
