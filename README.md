# Data Preprocessing Project

## Overview

This project focuses on data preprocessing techniques essential for preparing datasets for analysis and machine learning. The primary aim is to handle missing values, detect and treat outliers, normalize and scale features, and split the data into training and testing sets.

## Description
### Dataset

The dataset used in this project includes the following columns:
- `category`: The category of the product.
- `product_name`: The name of the product.
- `product_price`: The price of the product.
- `product_quantity`: The available quantity of the product.
- `number_reviews`: The number of reviews for the product.
- `product_ratings`: The average rating of the product.

### Steps Taken

1. **Handling Missing Values**:
   - Missing values in `product_price` were filled with the mean of the column.

2. **Outlier Detection and Treatment**:
   - The Interquartile Range (IQR) method was used to identify and remove outliers from the numerical columns.

3. **Normalization and Scaling of Features**:
   - Numerical features were standardized using `StandardScaler` to ensure they have a mean of 0 and a standard deviation of 1.

4. **Splitting the Data**:
   - The dataset was split into features (X) and target variable (y), followed by dividing it into training and testing sets using an 80/20 split.

## Instalation
### Requirements

To run this project, you will need:
- Python 3.x
- Pandas
- NumPy
- Scikit-learn

You can install the required packages using pip:

```bash
pip install pandas numpy scikit-learn
'''

## Usage

python data_preprocessing.py
