# Heart Disease Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of a heart disease dataset to identify key clinical and demographic factors associated with the presence of heart disease.

Using Python-based data analysis tools, the project uncovers patterns, correlations, and potential risk indicators that may contribute to cardiovascular conditions.

The analysis demonstrates a complete real-world data workflow — from data inspection and cleaning to visualization and insight extraction.

## 🎯 Objectives

- Understand the structure and characteristics of the dataset
- Analyze the distribution of medical and demographic features
- Investigate relationships between risk factors and heart disease
- Identify key predictors associated with heart disease
- Provide actionable insights through visual analytics

## 📂 Dataset Information

**Dataset:** Heart Disease Dataset ([Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset))

**Records:** Clinical data of patients

**Target Variable:** target

| Value | Meaning                   |
| ----- | ------------------------- |
| 0     | No heart disease          |
| 1     | Presence of heart disease |

## 🛠️ Tools & Technologies

- **Python**
- **Pandas & NumPy** — data manipulation
- **Matplotlib & Seaborn** — visualization
- **Jupyter Notebook** — analysis environment

## 🔍 Exploratory Data Analysis Workflow

### 🧹 Data Preparation

- Dataset loading and inspection
- Handling missing values(there was no missing value in this dataset)
- Duplicate detection and removal
- Data type verification

### 📊 Univariate Analysis

Analysis of individual variables to understand their distributions:

- Age distribution of patients
- Gender composition
- Cholesterol levels

### 🔁 Bivariate Analysis

Exploring relationships between features and heart disease:

- Age vs Heart Disease
- Gender vs Heart Disease
- Cholesterol vs Heart Disease
- Chest Pain Type vs Heart Disease

### 🔥 Multivariate Analysis

Understanding interactions among multiple variables:

- Feature correlation analysis
- Heatmap visualization
- Identification of strongest predictors

## 🧠 Key Insights

- Heart disease prevalence increases with age
- Male patients show higher incidence compared to females
- Certain chest pain types strongly correlate with heart disease
- Exercise-induced angina is a significant indicator
- Maximum heart rate achieved is inversely related to disease risk

## 📈 Sample Visualizations

The project includes:

- Distribution plots
- Count plots
- Box plots
- Correlation heatmaps

## 📁 Project Structure

Heart-Disease-EDA/
│
├── data/
│   └── heart.csv
│
├── notebook/
│   └── heart_disease_eda.ipynb
│
└── README.md

## 🚀 How to Run This Project

### Clone the repository

```bash
git clone https://github.com/your-username/heart-disease-eda.git
```

### Navigate to project directory

```bash
cd heart-disease-eda
```

### Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Open the notebook

```bash
jupyter notebook
```

## 📌 Future Improvements

- Apply machine learning models for prediction
- Feature importance analysis
- Model performance comparison

## 🎓 Skills Demonstrated

- Data cleaning and preprocessing
- Statistical analysis
- Data visualization
- Insight generation

## 📄 License

This project is for educational and research purposes.

## ⭐ Author

**Eiamin Hassan Shanto**
_Aspiring AI Engineer_

- GitHub: <https://github.com/EiaminHassan>
- LinkedIn: <https://www.linkedin.com/in/eiamin-hassan-shanto/>
