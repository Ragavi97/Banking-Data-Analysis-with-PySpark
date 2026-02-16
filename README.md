# Banking-Data-Analysis-with-PySpark

<h2>Project Overview</h2>

This project involves the exploration, cleaning, and processing of a banking dataset using PySpark. The primary goal is to prepare the data for further analysis or machine learning tasks, ensuring data quality and efficient processing of large datasets.

<h2>Dataset</h2>

The dataset contains various customer banking details, including demographic information, account information, and transactional data. The data was used to demonstrate data cleaning, transformation, and feature engineering using PySpark.

<h3>Key Attributes:</h3>
<ul><li>id</li>
  <li>installment</li>
  <li>grade</li>
  <li>home_ownership</li>
  <li>pymnt_plan</li>
</ul>

<h2> Project Structure </h2>

```
Project Structure
├── data/
│ └── banking_dataset.csv # Original dataset
├── notebooks/
│ └── banking_project.ipynb # Jupyter notebook with PySpark workflow
└── README.md # Project README
```

## Key Steps / Workflow

### 1. Data Loading
- Load the dataset into a PySpark DataFrame for distributed processing.

### 2. Data Exploration
- Check for missing values
- Identify data types
- Get summary statistics

### 3. Data Cleaning
- Handle missing or null values
- Correct inconsistent data entries
- Remove duplicates

### 4. Data Transformation
- Encode categorical variables
- Normalize or scale numerical features
- Feature engineering for relevant insights

### 5. Data Aggregation / Analysis
- Calculate summary metrics (e.g., average bala


