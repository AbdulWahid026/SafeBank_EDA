# 📊 Exploratory Data Analysis (EDA) — Fraud Detection Transactions Dataset

This project performs **Exploratory Data Analysis (EDA)** on a real-world **Fraud Detection Transactions Dataset**.
The goal is to explore, clean, preprocess, and analyze the data to uncover fraud patterns and prepare it for downstream machine-learning models.

## Dataset Overview

The dataset contains banking-related transaction records with the following information:

* Transaction details
* Device & card information
* Account balances
* Location data
* Historical fraud activity
* Timestamped records

# Project Structure

### Introduction & Basic Exploration

* Load dataset
* Display head and tail
* `.info()` and `.describe()`
* Identify numeric & categorical columns
* Datetime conversion & unique user count
* Importance of dataset exploration

### Selecting Data using `loc` and `iloc`

* Selecting first 15 rows with specific columns
* Filtering by location
* Transactions with high amount & high risk
* Difference between `loc` vs `iloc`
* Indexing importance

### GroupBy Operations

* Average transaction amount per location
* Fraud counts per transaction type
* Multilevel grouping: Device_Type × Card_Type
* Sorting grouped results
* Aggregation functions & trend detection

### Data Types

* Identify object & numeric types
* Convert timestamp to datetime
* Extract hour of day
* Importance of type conversion and memory optimization

### Outlier Detection & Handling

* Boxplots & histograms for numeric columns
* Rare category detection (<1%)
* Capping (1st & 99th percentile)
* Log transformation
* Scatter plots for compound outliers
* Handling extreme values & correlated outliers

### Missing Values

* Missing value percentages
* Imputing numeric (mean) & categorical (mode)
* Strategy for missing timestamps
* Flagging missing values
* Importance of imputation before modeling

### Inconsistency Detection

* Duplicate IDs & rows
* Invalid categorical values
* Logical contradictions
* Negative or unrealistic values
* Differentiating multiple transactions vs. data errors

### Visualization

Includes:

* Histograms
* Boxplots
* Bar charts
* Hourly transaction patterns
* Scatter plots

Discussion of:

* Outlier-focused visualizations
* Handling skewed distributions
* Visualizing high-cardinality categories

### Data Binning (`cut` and `qcut`)

* Equal-width bins
* Quantile-based bins
* High-risk transactions per bin
* Difference between `cut` vs. `qcut`
* Choosing bins for visualization vs. pattern detection

# Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib & Seaborn**
* **Jupyter Notebook / Google Colab**

# 📌 How to Run

1. Upload the dataset to Google Colab
2. Open the notebook
3. Install required libraries (if necessary)
4. Run all cells in sequential order

# Key Learnings from This EDA

* Understanding real-world financial fraud patterns
* Identifying outliers and inconsistencies in banking data
* Using grouping, filtering, and binning to detect anomalies
* Visualizing fraud distribution across locations, devices, and time
* Preprocessing steps essential before modeling


