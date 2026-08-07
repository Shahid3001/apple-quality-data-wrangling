# 🍎 Apple Quality Data Wrangling

A complete Data Wrangling project performed on the Apple Quality Dataset using Python.

This project demonstrates the complete preprocessing pipeline before Machine Learning, including handling missing values, datatype conversion, encoding categorical variables, and feature scaling.

---

## 📌 Project Objectives

- Load dataset
- Explore dataset
- Check dimensions and information
- Handle missing values
- Convert datatypes
- Encode categorical variables
- Normalize numerical features
- Prepare clean dataset for Machine Learning

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

---

## 📂 Dataset

Dataset Used:
- apple_quality.csv

---

## ⚙ Features Implemented

### Dataset Exploration

- Display first records
- Display last records
- Dataset shape
- Number of dimensions
- Column names
- Dataset information
- Statistical summary
- Data types

### Data Cleaning

- Detect missing values
- Count missing values
- Convert Acidity column to numeric
- Replace invalid values with NaN
- Fill missing values using Mean

### Feature Engineering

- Convert Quality column to Category datatype
- One-Hot Encoding using get_dummies()

### Feature Scaling

Applied Min-Max Normalization on:

- Size
- Weight
- Sweetness
- Crunchiness
- Juiciness
- Ripeness
- Acidity

using:

```python
MinMaxScaler()
```

---

## 📊 Libraries Used

```python
import pandas as pd
import numpy as np
from sklearn.preprocessing import MinMaxScaler
```

---

## ▶ How to Run

Clone repository

```bash
git clone https://github.com/yourusername/apple-quality-data-wrangling.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run

```bash
python data_wrangling.py
```

---

## 📈 Output

The program prints

- Dataset Preview
- Dataset Information
- Missing Values
- Statistical Summary
- Updated Data Types
- Normalized Dataset
- Final Processed Dataset

---

## Future Improvements

- Data Visualization
- Outlier Detection
- Feature Selection
- Machine Learning Models
- Interactive Dashboard

---

## Author

Mahammad Shahid Jamadar

Computer Engineering Student

JSPM JSCOE Pune
