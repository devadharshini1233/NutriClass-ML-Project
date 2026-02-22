🥗 NutriClass — Food Classification Using Nutritional Data
📌 Project Overview

NutriClass is a machine learning classification project that predicts the exact food item based on its nutritional attributes. The system uses structured nutritional data such as calories, protein, carbohydrates, fats, sugar, sodium, cholesterol, and other dietary indicators to classify foods into their correct categories.

This project demonstrates a complete ML pipeline including data preprocessing, feature engineering, multi-model training, evaluation, and business interpretation.

🎯 Objective

To build a multi-class classification model that:

Takes nutritional metrics as input

Predicts the exact food name as output

Supports strict diet planning scenarios

Enables automated food classification for health and nutrition systems

🧠 Business Use Cases

Smart diet planning applications

Health monitoring tools

Meal logging systems

Nutrition education platforms

Grocery and meal planning apps

Strict diet compliance systems

Unlike recommendation systems, this project focuses on one-to-one food classification for precise diet control.

📂 Dataset Features

The dataset contains tabular nutritional attributes including:

Calories

Protein

Fat

Carbohydrates

Sugar

Fiber

Sodium

Cholesterol

Glycemic Index

Water Content

Serving Size

Meal Type

Preparation Method

Vegan indicator

Gluten-free indicator

Target Column: Food_Name

⚙️ Project Pipeline
🔹 Data Preprocessing

Removed duplicates

Handled missing values

Converted boolean columns to numeric

One-hot encoded categorical variables

Label encoded target column

Standardized numerical features

🔹 Exploratory Data Analysis

Class distribution analysis

Feature distribution plots

Correlation heatmap

Nutritional variation across food types

🔹 Models Trained

Multiple classifiers were trained and compared:

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors

Support Vector Machine

Gradient Boosting

🔹 Evaluation Metrics

Models were evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Best model was selected based on test performance.

📊 Outputs Generated

Model accuracy comparison chart

Confusion matrix visualization

Feature importance (tree models)

Nutritional feature correlation heatmap

Real-time prediction example

🚀 Real-Time Prediction Capability

The trained model can take user-provided nutritional values and predict the exact food item. This supports real-time integration into diet tracking and meal planning applications.

🛠 Tools & Technologies

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook / VS Code
