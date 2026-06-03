
# 💳 Bank Loan Default Prediction Using Logistic Regression

## Project Overview

This project develops a machine learning model to predict whether a customer is likely to default on a loan based on employment status, bank balance, and annual salary.

The objective is to help financial institutions identify high-risk customers and support better lending decisions through predictive analytics.

---

## Business Problem

Loan default is a major risk for banks and financial institutions.

By analyzing customer financial information, we can build a predictive model that estimates the probability of loan default before issuing credit.

The model helps answer:

* Which customers are likely to default?
* How do salary and bank balance impact default risk?
* Does employment status affect loan repayment behavior?

---

## Dataset

The dataset contains customer financial information including:

| Feature       | Description           |
| ------------- | --------------------- |
| Employed      | Employment status     |
| Bank Balance  | Customer bank balance |
| Annual Salary | Annual income         |
| Defaulted?    | Target variable       |

---

## Technology Stack

### Data Analysis

* Python
* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-Learn
* Logistic Regression

### Version Control

* Git
* GitHub

---

## Exploratory Data Analysis

The project includes:

* Missing Value Analysis
* Descriptive Statistics
* Class Distribution Analysis
* Salary Distribution Analysis
* Bank Balance Distribution Analysis
* Correlation Heatmap

---

## Model Development

### Target Variable

```python
Defaulted?
```

### Features

```python
Employed
Bank Balance
Annual Salary
```

### Model

```python
Logistic Regression
```

### Train-Test Split

```python
test_size = 0.9
random_state = 107
```

---

## Machine Learning Workflow

```text
Raw Dataset
      │
      ▼
Data Exploration
      │
      ▼
Data Visualization
      │
      ▼
Feature Selection
      │
      ▼
Train/Test Split
      │
      ▼
Logistic Regression
      │
      ▼
Model Evaluation
      │
      ▼
Loan Default Prediction
```

---


### Salary Distribution

This visualization shows the distribution of customer annual salaries and helps identify income patterns within the dataset.

![Salary Distribution](model/Salary%20Distribution.png)


### Correlation Heatmap

This heatmap highlights the relationships between numerical variables and helps identify features that may influence loan default behavior.

![Correlation Heatmap](model/Correlation%20HeatMap.png)


### Confusion Matrix

The confusion matrix evaluates the performance of the Logistic Regression model by comparing actual and predicted loan default classifications.

![Confusion Matrix](model/Confusion%20Matrix.png)

---

## Model Evaluation

The model is evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

Metrics include:

* Precision
* Recall
* F1-Score

---

## Sample Predictions

### Customer 1

* Employed: Yes
* Annual Salary: $240,900
* Bank Balance: $100

Prediction:

```text
Low Risk
```

### Customer 2

* Employed: No
* Annual Salary: $0
* Bank Balance: $600,000

Prediction:

```text
High Risk
```

---

## Skills Demonstrated

### Data Analysis

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Statistical Analysis

### Machine Learning

* Logistic Regression
* Model Training
* Model Evaluation
* Classification Problems

### Data Visualization

* Seaborn
* Matplotlib
* Correlation Analysis

---
