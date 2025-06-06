# Thyroid Cancer Risk Data Analysis

## 📂 Overview
This project performs exploratory data analysis (EDA) on a dataset related to thyroid cancer risks. It investigates trends, distributions, and relationships between features that contribute to thyroid cancer diagnosis and risk levels.

## 📄 Dataset Description
- **Source File**: 'thyroid_cancer_risk_data.csv'
- **Target Column**: 'Thyroid_Cancer_Risk' (Values: 'Low', 'Medium', 'High')
- **Label Description**: Includes a binary 'Diagnosis' column (Benign / Malignant)
- **Key Features**:
  - Gender
  - Age
  - Family History
  - Radiation Exposure
  - Iodine Deficiency
  - Smoking
  - Obesity
  - Diagnosis
  - Risk Category

## 🔍 Exploratory Data Analysis (EDA)
Libraries used: numpy, pandas, matplotlib, seaborn, 

### ✔️ Initial Checks
- Data types, shape, missing values, and duplicates were inspected.
- Unique categories in categorical features were listed.

### 📊 Visualizations
- **Pie Chart**: Distribution of risk levels.
- **Count Plots**: Gender, Family History, Radiation Exposure, Iodine Deficiency, Smoking, Obesity.
- **Line Chart**: Average risk score by top 10 most common ages.

### 📈 Risk Mapping
- Risk Levels mapped to numerical values: 'Low = 1', 'Medium = 2', 'High = 3'.
- Average risk scores were calculated by age group.

## 📦 Dependencies
```bash
pandas
numpy
matplotlib
seaborn
```

## ✅ Key Insights
- Visualizations highlight patterns in gender and health history factors.
- Risk levels show distribution imbalance, important for further modeling.
- Age-wise analysis reveals trends in high-risk categories.

## 🚀 Future Work
- Perform feature correlation and statistical analysis.
- Apply machine learning classification models.
- Build an interactive dashboard or web app.

