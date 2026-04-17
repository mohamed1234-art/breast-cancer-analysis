
---

# 📊 Breast Cancer Data Analysis

## 🎯 Project Objectives

## Objectives:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization using graphs and charts
* Extracting insights from medical data

---

## 📌 Project Overview

This project analyzes breast cancer patient data to extract patterns and factors influencing survival months using data analysis and visualization techniques.

---

## 📈 Exploratory Data Analysis Insights

---

## 📊 1. Effect of Marital Status on Survival

### ❓ Research Question

Does marital status affect survival months of breast cancer patients?

### 💡 Findings

* Married patients: highest average survival (~72 months)
* Divorced / Single / Widowed: (~70–71 months)
* Separated patients: lowest survival (~63 months)

### 🔍 Insight

Marital status may indirectly influence survival due to psychological and social support, especially for married patients.

---

## 📊 2. Patient Status Distribution (Alive / Dead / Unknown)

### ❓ Research Question

What is the distribution of patient outcomes?

### 💡 Findings

* Alive: ~3200 cases (majority)
* Dead: ~600 cases
* Unknown: ~150 cases

### 🔍 Insight

Survival rate is very high (>80%), which may indicate early detection or dataset bias toward earlier stages.

---

## 📊 3. Tumor Stage vs Tumor Size

### ❓ Research Question

Does tumor stage correlate with tumor size?

### 💡 Findings

* T1 → ~16 mm
* T2 → ~30 mm
* T3 → ~53 mm (largest)
* T4 → ~43 mm (based on spread rather than size)

### 🔍 Insight

There is a clear positive relationship between tumor stage and size, confirming clinical consistency.

---

## 📊 4. Tumor Size vs Survival Months

### ❓ Research Question

Is tumor size related to survival duration?

### 💡 Findings

* Correlation = -0.079 (very weak negative relationship)

### 🔍 Insight

Tumor size alone is not a strong predictor of survival. Survival depends on multiple interacting factors such as stage, treatment, age, and hormonal status.

---

## 📊 5. Tumor Size by Grade

### ❓ Research Question

Does tumor grade affect tumor size?

### 💡 Findings

* Grade 1 → ~25 mm
* Grade 2 → ~27 mm
* Grade 3 → ~30 mm
* Grade 4 → ~36 mm

### 🔍 Insight

Higher tumor grades are associated with larger tumor sizes, indicating increased aggressiveness.

---

## 📊 6. Lymph Node Involvement vs Tumor Size

### ❓ Research Question

Is tumor size related to lymph node spread?

### 💡 Findings

* Correlation = 0.262 (weak to moderate positive relationship)

### 🔍 Insight

Larger tumors tend to spread more to lymph nodes, indicating higher disease severity.

---

## 📊 7. Tumor Size by Patient Status

### ❓ Research Question

Does tumor size differ by survival outcome?

### 💡 Findings

* Dead: ~33 mm (largest)
* Unknown: ~30 mm
* Alive: ~27 mm (smallest)

### 🔍 Insight

Patients who died had larger tumors on average, confirming tumor size as a risk factor.

---

## 📊 8. Correlation Heatmap Analysis

### ❓ Research Question

What are the strongest relationships between variables?

### 💡 Findings

* Regional_node_examined & Reginol_node_positive → 0.3 (strongest)
* Tumor_size & Reginol_node_positive → 0.26
* Survival_months shows weak correlation with all variables

### 🔍 Insight

Survival is a complex outcome influenced by multiple weakly related factors rather than a single dominant variable.

---

## 📊 9. Age vs Survival Months

### ❓ Research Question

Does age affect survival time?

### 💡 Findings

* Correlation = -0.0108 (almost zero)

### ⚠️ Important Note

The statement "older patients tend to have shorter survival" is not supported by the data.

### 🔍 Insight

Age alone is not a statistically significant predictor of survival in this dataset.

---

## 🔑 Overall Conclusion

Survival in breast cancer is a **multifactorial outcome** that cannot be explained by a single variable.

### 🔴 Main Risk Factors:

* Large tumor size
* High tumor grade
* Lymph node involvement
* Indirect social factors (e.g., marital status)

---

## 🛠️ Tools Used

* Pandas → Data cleaning & analysis
* NumPy → Numerical operations
* Matplotlib → Data visualization
* Seaborn → Statistical visualization
* Plotly → Interactive charts

---

## ⚠️ Disclaimer

This project is for educational data analysis purposes only and should not be used for medical diagnosis or treatment decisions.

---

