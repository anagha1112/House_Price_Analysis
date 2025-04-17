# 🏠 House Price Data Analysis (Coursera Project)

This repository contains my submission for the **"Data Analysis with Python"** course on Coursera. The project involves analyzing a house sales dataset to answer 10 specific questions using Python, Pandas, Seaborn, and Scikit-Learn.

## 📄 Project Description

The goal is to apply real-world data analysis skills, including data wrangling, visualization, and machine learning techniques to explore housing price trends and build predictive models.

## 📌 Questions Addressed

1. Display the data types of each column using `dtypes`.
2. Drop the columns `"id"` and `"Unnamed: 0"`, then use `describe()` for summary stats.
3. Count the number of houses with unique floor values using `value_counts()` and convert the result to a DataFrame.
4. Use a **boxplot** to examine if waterfront view affects price outliers.
5. Use a **regplot** to determine the correlation between `sqft_above` and `price`.
6. Fit a **linear regression model** to predict `price` using `sqft_living`, calculate **R²**.
7. Fit a linear regression model using a list of multiple features.
8. Use a **pipeline** to fit the model and calculate R² with multiple features.
9. Create and evaluate a **Ridge regression** model (alpha = 0.1) on test data.
10. Perform a **polynomial transform (degree=2)**, fit Ridge regression, and calculate R² on test data.

Each question is answered in code cells, with visual outputs where needed (e.g., plots and printed R² values). Screenshots of outputs were taken for submission as required by the course.

## 🧪 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-Learn


## 🚀 Running the Notebook

You can run this notebook on [Google Colab](https://colab.research.google.com/) or locally:

1. Clone this repo:
   ```bash
   git clone https://github.com/anagha1112/House_Price_Analysis


