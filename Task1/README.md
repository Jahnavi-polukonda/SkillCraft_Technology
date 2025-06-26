# 🏡 House Price Prediction – SkillCraft Internship Task 1
This repository contains the solution to Task 1 of the Machine Learning Internship at SkillCraft Technology.
The objective is to implement a Linear Regression model to predict the house prices based on the following features:

📐 Square Feet

🛏️ Number of Bedrooms
🛁 Number of Bathrooms

# 📁 Dataset
File used: house_price_dataset.csv
🧠 Technologies & Libraries Used
Python
Google Colab
pandas, numpy
matplotlib, seaborn (for data visualization)
scikit-learn (for model training and evaluation)

# 🧪 Project Workflow
## 1. Data Upload and Preprocessing
Dataset uploaded via Colab.
Displayed the first few rows.
Checked data types and null values using data.info().
## 2. Data Visualization
Used seaborn.pairplot() to observe relationships between features and price.
## 3. Feature Selection
Selected SquareFeet, Bedrooms, and Bathrooms as independent variables (X).
Price is the target variable (y).
## 4. Model Building
Split the dataset into training and testing sets (80-20 split).
Applied Linear Regression using sklearn.linear_model.LinearRegression.
ccuracy)
Mean Squa
## 5. Model Evaluation
Evaluated using:
R² Score (for accuracy)
Mean Squared Error (for error)
## 6. Prediction
Predicted prices on the test data and visualized the difference between actual and predicted values.

# 📊 Output Summary
Model showed good performance with reasonable accuracy.
Visualizations helped identify linear relationships between features.
