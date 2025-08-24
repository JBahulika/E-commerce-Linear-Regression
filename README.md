# E-commerce-Linear-Regression

## 📋 Project Overview

This project's primary goal is to apply a simple linear regression model to predict the "Yearly Amount Spent" by an e-commerce customer. The analysis aims to help a clothing company understand which of its platforms—the mobile app or the website—is more effective at driving customer spending, informing future investment decisions.

The project follows a standard data science workflow, including data exploration, model building, and evaluation. Key findings and a business recommendation are also included.

## 📊 Key Findings

The model's analysis of feature coefficients reveals that **"Length of Membership" is the most influential factor** in predicting how much a customer spends annually.

Furthermore, the model suggests that **time spent on the mobile app has a significantly greater positive impact** on yearly spending compared to time spent on the website.

## 📈 Methodology

1.  **Data Collection**: The project uses the "E-commerce Customers" dataset, which contains customer information and spending habits.
2.  **Exploratory Data Analysis (EDA)**: Data is loaded and inspected using Pandas. Visualizations like joint plots and a pair plot are created with Matplotlib and Seaborn to understand the relationships between the features.
3.  **Model Building**: The dataset is split into training and testing sets. A `LinearRegression` model from `scikit-learn` is trained on the training data.
4.  **Model Evaluation**: Predictions are made on the test set, and the model's performance is assessed visually through a scatter plot of actual vs. predicted values and quantitatively using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
5.  **Residual Analysis**: A histogram of the residuals is plotted to confirm the model's assumptions by checking for a normal distribution.

## 📁 Repository Contents

-   `LRecommerce.ipynb`: The main Jupyter Notebook containing all the code for data loading, EDA, model training, and evaluation.
-   `ecommerce.csv`: The dataset used in the project.

## 📦 Requirements

This project requires a Python environment with the following libraries:

-   `pandas`
-   `matplotlib`
-   `seaborn`
-   `scikit-learn`
-   `numpy`
-   `scipy`
-   `pylab`
