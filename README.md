# 🩺 Health Insurance Cost Analysis

This project analyzes a health insurance dataset to explore how various factors such as **age, BMI, smoking status, and number of children** influence **medical insurance charges**. Conducted as part of the **IBM Data Analyst Professional Certificate** on Coursera, this project demonstrates foundational skills in data cleaning, visualization, and linear regression modeling using Python.

---

## 📘 Project Overview

- **Dataset Source**: IBM Developer Skills Network (via Coursera)
- **Tools & Libraries**:  
  `pandas`, `matplotlib`, `seaborn`, `scikit-learn`  
  Environment: **JupyterLite** (Pyodide kernel)
- **Goal**:  
  1. Perform Exploratory Data Analysis (EDA)  
  2. Identify key cost drivers  
  3. Build a Linear Regression model to predict medical insurance charges  

---

## 📊 Dataset Features

| Column            | Description                                      |
|-------------------|--------------------------------------------------|
| `Age`             | Age of the insured person                        |
| `Gender`          | 1 = Male, 2 = Female                             |
| `BMI`             | Body Mass Index                                  |
| `No_Of_Children`  | Number of children/dependents                    |
| `Smoker`          | 1 = Smoker, 0 = Non-Smoker                       |
| `Region`          | 1 = Northeast, 2 = Northwest, 3 = Southeast, 4 = Southwest |
| `Charges`         | Annual medical insurance charges (in USD)        |

---

## 📈 Key Visualizations

- 📊 **Histogram** of Charges Distribution  
- 📉 **Scatterplots**: Charges vs Age, Charges vs BMI  
- 🧾 **Boxplot**: Smoker vs Charges  
- 🔥 **Correlation Heatmap** for all numerical features

---

## 🔍 Insights Gained

- **Smokers** pay significantly more for insurance than non-smokers.
- A **BMI over 30** (obese) further increases charges, especially for smokers.
- **Age** shows a linear correlation with medical expenses.
- **Number of children** has minimal impact on cost.

---

## 🤖 Machine Learning Model

A **Linear Regression** model was implemented to predict insurance charges.

**Preprocessing Steps**:
- Encoded categorical features (`Gender`, `Smoker`, `Region`)
- Scaled numerical features using `StandardScaler`
- Optionally applied polynomial feature expansion

**Model Evaluation**:
- R² Score  
- Mean Absolute Error (MAE)

---

## 📁 Repository Files

- [`Health_Insurance.ipynb`](https://github.com/VidyaVGeetha/Health-Insurance-Cost-Analysis/blob/main/Health_Insurance.ipynb) – Full code and analysis  
- `medical_insurance_dataset.csv` – Raw dataset (not uploaded; link inside notebook)

---

## 🛠️ How to Run

1. Clone this repository or download the notebook
2. Open `Health_Insurance.ipynb` in Jupyter or JupyterLite
3. Install required packages:
    ```bash
    pip install pandas matplotlib seaborn scikit-learn
    ```
4. Run all cells sequentially to reproduce analysis and results

---

## 👩‍💻 About Me

**Vidya V.G.**  
📍 Based in Scotland, UK  
📚 IBM Data Analyst Professional Certificate (Coursera)  
💼 Seeking entry-level **Data Analyst** roles  
🔗 [GitHub Portfolio](https://github.com/VidyaVGeetha)

---

## ⭐️ Star This Repo

If you find this project useful, feel free to ⭐️ star it and follow for more projects!

