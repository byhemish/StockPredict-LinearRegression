Markdown
# Stock Price Prediction Using Machine Learning

A machine learning project that predicts future stock closing prices using a Linear Regression model built with scikit-learn. The pipeline includes data loading, shift-based preprocessing for a 30-day forecast horizon, and future value visualization.

---

## Features
* Data Preprocessing: Handles historical stock data and creates a shifted target column to forecast 30 days into the future.
* Predictive Modeling: Uses a Linear Regression model to identify trends and predict future closing prices.
* Data Visualization: Built-in plotting using Matplotlib to compare actual vs. predicted prices.

---

## Model Performance & Results
The model was trained and evaluated on historical data with the following metrics:
* R² Score: 0.9529 (indicating a strong fit and high accuracy in trend tracking)
* Mean Squared Error (MSE): 111.72

---

## Tech Stack & Libraries
* Language: Python
* Machine Learning: scikit-learn
* Data Manipulation: pandas, numpy
* Visualization: matplotlib

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
   cd YOUR_REPOSITORY_NAME
Install dependencies:

Bash
pip install pandas numpy scikit-learn matplotlib
Run the notebook or script:
You can open and run the Stock Price Prediction.ipynb file in Jupyter Notebook , Google Colab or Vs Code .
