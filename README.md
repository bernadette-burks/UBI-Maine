# 🌱 Universal Basic Income (UBI) in the State of Maine  
### *Data Analysis & Visualizations in Support of UBI Implementation*  

![Python 3.13](https://img.shields.io/badge/Python-3.13-blue?style=flat-square&logo=python&logoColor=white) 
![NumPy 1.26.4](https://img.shields.io/badge/NumPy-1.26.4-orange?style=flat-square&logo=NumPy&logoColor=white) 
![Pandas 2.1.1](https://img.shields.io/badge/Pandas-2.1.1-lightblue?style=flat-square&logo=pandas&logoColor=white) 
![Matplotlib 3.8.1](https://img.shields.io/badge/Matplotlib-3.8.1-red?style=flat-square&logo=matplotlib&logoColor=white) 
![Seaborn 0.13.2](https://img.shields.io/badge/Seaborn-0.13.2-purple?style=flat-square&logo=seaborn&logoColor=white) 
![Scikit-learn 1.3.2](https://img.shields.io/badge/Scikit--learn-1.3.2-green?style=flat-square&logo=scikit-learn&logoColor=white)  
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter&logoColor=white) 
![Project](https://img.shields.io/badge/Project-Data%20Analysis-violet?style=flat-square)
![Status](https://img.shields.io/badge/Status-Professional%20-informational?style=flat-square&logo=none)
![Data Source](https://img.shields.io/badge/Data-Census%20ACS-pink?style=flat-square)
![Methods](https://img.shields.io/badge/Methods-Regression%20Analysis-orange?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Universal%20Basic%20Income-purple?style=flat-square)
![Region](https://img.shields.io/badge/Region-Maine-lightgrey?style=flat-square)

**Author:** Bernadette Burks  
**Date:** February 11, 2026 

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Required Technologies](#-required-technologies)
- [Python Libraries](#-python-libraries)
- [Dataset Details](#-dataset-details)
- [Data Preparation & Cleaning](#-data-preparation--cleaning)
- [Example Workflow](#-example-workflow)
- [Results](#-results)
- [Future Improvements](#-future-improvements)
- [References](#-references)

---

## 📌 Project Overview

For this assignment, I developed **5 Scenarios for UBI Policy Implementation** based on Census ACS data available at:  
[https://fred.stlouisfed.org/data/MEHOINUSMEA646N](https://fred.stlouisfed.org/data/MEHOINUSMEA646N)

I chose to work on this project professionally - with a passion for my home state of Maine and an interest in financial equity for all humans.

The primary goal of this analysis is to explore how the Median Household Income for Maine (between 1984-2024) can be visualized effectively to highlight a genuine benefit from possible UBI implementation.

---

## ⚙️ Required Technologies

For development, I used **VS Code (Python 3.13)** as this is a frequently used IDE in enterprise settings and my own personal preference.

---

## 📚 Python Libraries

This project incorporates several straightforward and well-supported Python libraries:

- **Pandas** – Provides efficient data structures and visualization support built on NumPy.  
- **NumPy** – Enables fast numerical operations and compact dataset handling.  
- **Matplotlib** – Offers highly customizable plotting tools compatible with most ML libraries.  
- **Seaborn** – Builds upon Matplotlib for more complex statistical visualizations.  
- **Scikit-learn** – Supplies integrated machine learning algorithms and model evaluation tools.

---

## 🗂 Dataset Details

The dataset used in this project is entitled **MEHOINUSMEA646N** and contains a single file with **41 total entries**.

### Features Included

The dataset consists of 2 US Census-gathered variables:

- DATE (of annual census report)  
- VALUE (median household income value)   

The outcome variable is:

- **Favoring UBI Implementation in Maine** (based on the analysis and supporting visualizations of 5 scenarios)

---

## 🧹 Data Preparation & Cleaning

**Data Exploratory Analysis Using Seaborn (Optional, But Informative)**
- Identify Missing Values  
- Visualize Outliers  
- Feature Scaling (Normalization or Standardization)  
- Correlation Analysis (Matrix)  


**Data Preprocessing with Pandas and Scikit-learn (Core Preprocessing Steps)**
- Handle Missing Data: Use df.isnull().sum() to identify missing data and df.fillna(value) or df.dropna() to address them.  
- Encoding Categorical Variables: Convert categorical text data into numerical format using pd.get_dummies() for one-hot encoding, or label encoding.  
- Feature Scaling: Normalize or standardize numerical columns using scikit-learn's StandardScaler (Z-score normalization) or MinMaxScaler.  
- Data Splitting: Split data into training and testing sets using train_test_split from sklearn.model_selection.  

---

## 🧪 Example Workflow

Each of 5 scenarios consist of: analysis + visualization  

### Analysis

```python
```

### Visualization

```python
```

---

## 📊 Results

Results of this analysis showed that all 5 scenarios and supporting visualizations argue in favor of providing various types of Universal Basic Income (UBI) to Mainers. (To be edited more after analysis is complete).

### Scenario 1

TBD.

![Visualization Title](results/imagename.png)

---

### Scenario 2

TBD.

![Visualization Title and Image Here](results/imagename.png)

---

### Scenario 3

TBD.

![Visualization Title and Image Here](results/imagename.png)

---

### Scenario 4

TBD.

![Visualization Title and Image Here](results/imagename.png)

---

### Scenario 5

TBD.

![Visualization Title and Image Here](results/imagename.png)

---

## 🚀 Future Improvements

This project serves as an excellent starting point for continued development. Future enhancements may include:

- Updates to data as AI changes job outlook in various sectors  
- Updates to data as AI creates new job opportunities
- More robust datasets to enhance existing variables  
- Visualizations with Live Update features (web-based tool version) 

---

## 🔗 References

*Table Data - Median Household Income in Maine.* (n.d.). FRED, St. Louis Fed. Retrieved February 12, 2026 from https://fred.stlouisfed.org/data/MEHOINUSMEA646N  
