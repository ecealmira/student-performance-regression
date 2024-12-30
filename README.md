# Regression Models for Student Performance Dataset

This notebook implements and analyzes various regression models for a dataset related to student performance.

## Contents

### 1. Introduction

The notebook demonstrates steps for:

- Data exploration
- Visualization
- Regression model implementation
- Model evaluation

### 2. Dataset

- **Name**: `Student_performance_data.csv`
- **Description**: Contains data on student demographics and performance metrics.
- **Key Features**:
  - `Age`: Numeric feature representing student age.
  - `Gender`: Categorical feature representing the gender of the student.
  - Performance-related metrics

### 3. Notebook Workflow

#### 3.1 Data Loading and Inspection

- The dataset is loaded using `pandas`.
- Inspections include:
  - Data types
  - Missing values
  - Initial sample view (`df.head()`).

#### 3.2 Data Visualization

- Distribution plots:
  - Age distribution using `sns.countplot`.
  - Gender distribution using a pie chart.
- Other visualizations as needed for exploratory data analysis.

#### 3.3 Regression Models

- Implements the following models:
  - **Linear Regression**
  - **K-Nearest Neighbors (KNN) Regression**
  - **Decision Tree Regression**
- The notebook uses:
  - `train_test_split` for splitting the data.
  - Evaluation metrics: 
    - Mean Squared Error (MSE)
    - Mean Absolute Error (MAE)
    - R-squared.

#### 3.4 Hyperparameter Tuning
Includes grid search or cross-validation to optimize model performance.
