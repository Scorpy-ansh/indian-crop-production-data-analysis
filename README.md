# 🌾 Indian Crop Production Data Analysis

> A comprehensive data collection, cleaning, preprocessing, and exploratory data analysis (EDA) project on the Indian Crop Production and Yield dataset using Python.

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

---

# 📖 Project Overview

This project was completed as part of a **Machine Learning Data Analyst Internship**.

The objective was to collect a real-world agribusiness dataset, perform a complete data quality assessment, clean the dataset, conduct exploratory data analysis (EDA), and prepare it for future machine learning applications.

Instead of applying generic preprocessing techniques, every cleaning decision was based on careful data inspection and statistical analysis.

---

# 📂 Dataset Information

**Dataset:** Indian Crop Production and Yield Dataset

| Property | Value |
|----------|-------|
| Records | **575,879** |
| Features | **8** |
| States | **36** |
| Districts | **730** |
| Crop Types | **128** |
| Seasons | **6** |

### Dataset Features

- State_Name
- District_Name
- Crop_Year
- Season
- Crop
- Area
- Production
- Yield

---

# 🎯 Project Objectives

- Collect a real-world agricultural dataset
- Understand dataset structure
- Perform data quality assessment
- Detect missing values
- Detect duplicate records
- Investigate zero values
- Detect statistical outliers
- Perform exploratory data analysis
- Apply suitable preprocessing techniques
- Export a cleaned dataset

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code

---

# 📊 Data Quality Assessment

✔ Missing Values Analysis

✔ Duplicate Record Detection

✔ Data Type Verification

✔ Zero Value Investigation

✔ Negative Value Detection

✔ Outlier Detection (IQR Method)

---

# 📈 Exploratory Data Analysis

The following analyses were performed:

- Dataset overview
- Statistical summary
- Histograms
- Boxplots
- Correlation Matrix
- Top 10 States
- Top 10 Crops
- Seasonal Distribution
- Area vs Production Scatter Plot
- Log Transformation Analysis

---

# 🧹 Data Cleaning Process

The dataset was carefully evaluated before applying any preprocessing.

### Completed Steps

- No missing values found
- No duplicate records found
- No negative values detected
- Investigated zero production records
- Detected statistical outliers
- Applied logarithmic transformation
- Exported cleaned dataset

---

# 📌 Key Findings

- Dataset contains **575,879** agricultural records.
- No missing values were present.
- No duplicate records were found.
- No invalid negative values existed.
- **3,634** records contained zero production and yield values and were retained as valid observations.
- Numerical variables were highly skewed.
- Logarithmic transformation improved feature distributions for future machine learning tasks.

---

# 📁 Project Structure

```
Indian-Crop-Production-Data-Analysis/
│
├── data/
│   └── Indian_crop_production_yield_dataset.csv
│
├── cleaned_data/
│   └── Indian_crop_production_yield_cleaned.csv
│
├── notebooks/
│   └── Week1_DataCleaning.ipynb
│
├── reports/
│   └── Week1_Report.docx
│
├── images/
│   ├── boxplots
│   ├── histograms
│   ├── correlation_heatmap
│   ├── top_states
│   ├── top_crops
│   └── seasons
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/yourusername/Indian-Crop-Production-Data-Analysis.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
notebooks/Week1_DataCleaning.ipynb
```

---

# 📷 Project Results

> Add screenshots here after uploading them.

Example:

- Dataset Overview
- Missing Value Analysis
- Correlation Matrix
- Boxplots
- Histograms
- Top States
- Top Crops

---

# 📌 Future Improvements

- Crop Yield Prediction
- Production Forecasting
- Machine Learning Models
- Interactive Dashboard
- Time Series Analysis
- Geographical Visualization

---

# 📚 References

- Kaggle – Indian Crop Production and Yield Dataset
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Seaborn Documentation
- Scikit-learn Documentation

---

# 👨‍💻 Author

**Anshuman Pattanayak**

B.Tech Computer Science & Engineering

Machine Learning & Data Analytics Enthusiast

GitHub: https://github.com/yourusername

---

⭐ If you found this project useful, consider giving it a star!
