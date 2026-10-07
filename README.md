
# 🏠 House Price Prediction Using Machine Learning

## 📌 Project Overview

This project develops a **Multiple Linear Regression** model to predict house prices using a real-world open-access dataset.

The model uses multiple property-related features to estimate the price of a house. The predictive performance of the model is evaluated using standard regression metrics such as **Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score**.

---

## 🎯 Objectives

- Develop a Multiple Linear Regression model for house price prediction.
- Use a suitable real-world open-access dataset.
- Perform data preprocessing and prepare the dataset for machine learning.
- Split the dataset into training and testing sets.
- Train the Multiple Linear Regression model.
- Predict house prices using the trained model.
- Evaluate the predictive capability of the model using:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score

---

## 📊 Dataset

The project uses a **real-world open-access house price dataset** containing property-related information.

The dataset includes features that can influence house prices, such as:

- Area / Size of the house
- Number of bedrooms
- Number of bathrooms
- Location-related information
- Other property characteristics

> **Note:** The exact features depend on the dataset used in this project.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation and preprocessing
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Data visualization
- **Scikit-learn** – Machine learning and model evaluation
- **Jupyter Notebook** – Development environment

---

## ⚙️ Methodology

The project follows these steps:

### 1. Data Collection
A real-world open-access house price dataset is collected for developing the prediction model.

### 2. Data Preprocessing
The dataset is inspected and cleaned before applying the machine learning algorithm.

Preprocessing includes:

- Handling missing values
- Selecting relevant features
- Removing unnecessary columns
- Converting data into suitable numerical form

### 3. Exploratory Data Analysis

The dataset is analyzed to understand relationships between different features and house prices.

Visualizations such as correlation heatmaps and scatter plots can be used to identify important relationships.

### 4. Feature Selection

Relevant independent variables are selected as input features (`X`), while house price is selected as the target variable (`Y`).

### 5. Train-Test Split

The dataset is divided into:

- **Training data** – Used to train the model
- **Testing data** – Used to evaluate the model

### 6. Model Development

A **Multiple Linear Regression** model is trained using the training dataset.

The general form of the model is:

**House Price = b₀ + b₁X₁ + b₂X₂ + ... + bₙXₙ**

where:

- `b₀` = Intercept
- `b₁, b₂, ..., bₙ` = Regression coefficients
- `X₁, X₂, ..., Xₙ` = Input features

### 7. Prediction

The trained model is used to predict house prices for the test dataset.

### 8. Model Evaluation

The model is evaluated using three regression metrics:

#### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

Lower MSE indicates better performance.

#### Root Mean Squared Error (RMSE)

RMSE is the square root of MSE and represents the prediction error in the same unit as the target variable.

Lower RMSE indicates better performance.

#### R² Score

R² measures how well the independent variables explain the variation in house prices.

A value closer to **1** generally indicates better model performance.

---

## 📈 Evaluation Metrics

The following metrics are calculated after testing the model:

| Metric | Purpose |
|---|---|
| MSE | Measures average squared prediction error |
| RMSE | Measures prediction error in target units |
| R² Score | Measures how well the model explains the target variation |

### Results

Add your actual results here after running the model:

```text
Mean Squared Error (MSE): YOUR_VALUE
Root Mean Squared Error (RMSE): YOUR_VALUE
R² Score: YOUR_VALUE
