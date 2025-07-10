# AI_HousePriceEstimator

# 🧠 AI_HousePriceEstimator

A hands-on project by **Matheesha** to demonstrate how to build a simple **Linear Regression** model that estimates house prices using **synthetic data**. The model learns to predict house prices based on square footage and the number of bedrooms.

---

## 📌 Table of Contents

- [📖 Overview](#-overview)
- [🛠️ Technologies Used](#-technologies-used)
- [📁 Project Structure](#-project-structure)
- [⚙️ How It Works](#-how-it-works)



---

## 📖 Overview

This project demonstrates how to:
- Generate a **synthetic dataset** to simulate real-world housing data.
- Build and train a **Linear Regression** model using `scikit-learn`.
- Predict house prices based on:
  - House Size in square feet
  - Number of Bedrooms
- Evaluate model performance using standard metrics.

---

## 🛠️ Technologies Used

- Python 3.x
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [scikit-learn](https://scikit-learn.org/)
- [Matplotlib](https://matplotlib.org/)

---



## ⚙️ How It Works

### 🔹 Section 1: Import Libraries
Essential libraries for data manipulation, model building, evaluation, and visualization are imported.

### 🔹 Section 2: Generate Synthetic Data
Instead of a real dataset, random data is generated for:
- `Size_sqft`: from 800 to 3000 sqft
- `Num_Bedrooms`: between 2 and 5
- `Price_USD`: calculated using a custom formula with added noise

### 🔹 Section 3: Define Features & Target
- `X`: Input features — Size and Bedrooms
- `y`: Target — House Price

### 🔹 Section 4: Train-Test Split
- Split the dataset into 80% training and 20% testing sets using `train_test_split`.

### 🔹 Section 5: Model Initialization
- A `LinearRegression` model object is created.

### 🔹 Section 6: Model Training
- The model is trained using `.fit()` on training data.
- Coefficients and intercept are printed.

### 🔹 Section 7: Model Prediction
- Predictions are made on the test set.
- A sample of actual vs. predicted values is printed.

---



