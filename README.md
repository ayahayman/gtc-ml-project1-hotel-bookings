# Hotel Bookings Data Analysis & Machine Learning Project

## Overview
This project analyzes and preprocesses a hotel bookings dataset to uncover insights and prepare the data for machine learning tasks. The workflow includes exploratory data analysis (EDA), data cleaning, feature engineering, and data preprocessing.

## Dataset
- **File:** `hotel_bookings.csv`
- Contains hotel booking records with features such as booking dates, guest details, stay duration, and reservation status.

## Project Phases

### 1. Exploratory Data Analysis (EDA) & Data Quality Report
- Inspects data shape, columns, and summary statistics.
- Visualizes missing values and outliers using `missingno` and boxplots.
- Identifies main data quality issues (e.g., missing values, outliers).

### 2. Data Cleaning
- Fills missing values for `agent`, `company`, `country`, and `children` columns.
- Removes duplicate records.
- Handles outliers in `adr` (average daily rate) and `lead_time` columns.
- Converts date columns to appropriate types.

### 3. Feature Engineering & Preprocessing
- Creates new features: `total_guests`, `total_nights`, and `is_family`.
- Encodes categorical variables using one-hot encoding and frequency encoding.
- Groups rare countries into an "Other" category.
- Drops unnecessary columns.
- Splits the data into training and testing sets.

## Notebooks
- All code and analysis are in `gtc_ml_project1_hotel_bookings.ipynb`.

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn, missingno, scikit-learn

## How to Run
1. Install required libraries:
	```bash
	pip install pandas numpy matplotlib seaborn missingno scikit-learn
	```
2. Open the notebook in Jupyter or VS Code and run the cells sequentially.

## Author
This project was completed as part of the GTC Summer Internship 2025.
