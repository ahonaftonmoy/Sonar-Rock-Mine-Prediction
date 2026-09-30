# Sonar Rock vs Mine Prediction

A machine learning project that uses Logistic Regression to classify an object as either a rock or a mine based on sonar signal data.

## 📌 Project Overview

This project uses the Sonar dataset to build a machine learning model that can distinguish between rocks and metal mines.

The dataset contains 60 numerical features representing sonar signal measurements. A Logistic Regression model is trained using these features and then used to predict whether a new object is a rock or a mine.

## 📊 Dataset

The dataset used in this project is the **Sonar Dataset**.

It contains:

* 60 numerical features based on sonar measurements
* 1 target column indicating the object type
  - `R`= Rock
  - `M`= Mine

The dataset contains 208 observations.

## 🤖 Machine Learning Model

The project uses **Logistic Regression** for binary classification.

The dataset is divided into:

- **90% training data**
- **10% testing data**

The `train_test_split` function is used with stratification to maintain the class distribution between the training and testing sets.

## 🔄 Project Workflow

The project follows these steps:

1. Load the dataset using Pandas
2. Explore the dataset
3. Check for missing values
4. Analyze the target classes
5. Separate features and labels
6. Split the dataset into training and testing sets
7. Train a Logistic Regression model
8. Evaluate the model using accuracy
9. Use the trained model to make a prediction on a new sonar sample

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab / Jupyter Notebook

## 📈 Model Evaluation

The model is evaluated using **accuracy score** on both the training and testing datasets.

The exact accuracy values can be found in the notebook output.

## 🔮 Example Prediction

The project also includes a sample sonar measurement containing 60 features.

The trained model predicts whether the object represented by the sonar measurements is:

- **Rock**
- **Mine**
