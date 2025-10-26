# 🧠 Employee Attrition Prediction using Machine Learning

> *“Built during my internship as a Data Science Intern at HexSoftwares Company.”* 💼

---

## 📋 Project Overview

Employee attrition — the rate at which employees leave a company — can significantly affect productivity, morale, and financial performance.

In this project, I used **Machine Learning (Logistic Regression)** to analyze employee data and **predict whether an employee is likely to leave or stay**. The project focuses on identifying the main factors influencing attrition so HR teams can take proactive steps to retain valuable talent.

This model transforms HR data into **actionable insights**, helping organizations make data-driven workforce decisions.

---

## 📂 Dataset Information

**Dataset Name:** HR-Employee-Attrition.csv
**Total Records:** 1470
**Attributes:** 35

The dataset includes various attributes that describe employees' background, work conditions, and satisfaction levels.

| Category                          | Features                                                    |
| --------------------------------- | ----------------------------------------------------------- |
| 👥 **Demographics**               | Age, Gender, MaritalStatus                                  |
| 💼 **Job Details**                | Department, JobRole, JobLevel, TotalWorkingYears            |
| 💰 **Compensation**               | MonthlyIncome, PercentSalaryHike, StockOptionLevel          |
| 🕒 **Work Patterns**              | OverTime, DistanceFromHome, YearsAtCompany                  |
| 📈 **Performance & Satisfaction** | JobSatisfaction, EnvironmentSatisfaction, PerformanceRating |

---

## ⚙️ Technologies and Libraries Used

* **Python 3** 🐍
* **Pandas** – Data manipulation
* **NumPy** – Numerical computation
* **Matplotlib** & **Seaborn** – Data visualization
* **Scikit-learn** – Model building and evaluation

---

## 🔬 Data Preprocessing

✅ Removed unnecessary and duplicate columns
✅ Encoded categorical variables (e.g., Gender, Department, OverTime)
✅ Checked for missing values and ensured data consistency
✅ Split data into training and testing sets
✅ Scaled numerical features for better model performance

---

## 📊 Exploratory Data Analysis (EDA)

Several important patterns emerged during the exploratory data analysis:

### 🔎 Key Visual Insights:

* **Attrition vs Overtime:** Employees working overtime are **3× more likely** to leave than those who don’t.
* **Job Satisfaction:** Low job satisfaction is a strong indicator of attrition.
* **Environment Satisfaction:** Employees with poor work environments are more likely to resign.
* **Promotion Wait Time:** Lack of career growth or delayed promotions leads to higher turnover.
* **Salary Paradox:** Even well-paid employees in high-stress roles show higher attrition rates.

---

## 🧠 Model Used — Logistic Regression

I used **Logistic Regression**, a simple yet powerful algorithm for binary classification, to predict whether an employee will stay or leave.

### ⚙️ Model Workflow:

1️⃣ Split the data into training (80%) and testing (20%) sets.
2️⃣ Trained the **Logistic Regression** model using `scikit-learn`.
3️⃣ Evaluated the model using accuracy, precision, recall, F1-score, and confusion matrix.

---

## 📈 Model Evaluation

| Metric        | Value |
| ------------- | ----- |
| **Accuracy**  | 89%   |
| **Precision** | 0.91  |
| **Recall**    | 0.41  |
| **F1-Score**  | 0.49  |

🔹 The model performs well overall, correctly predicting most employee outcomes while identifying key risk factors for attrition.

---

## 💡 Key Findings

### 1️⃣ Overtime is the Biggest Red Flag

Employees who work overtime are around **three times more likely** to leave the company.

### 2️⃣ Job & Environment Satisfaction are Critical

Low satisfaction levels, both job-related and environmental, significantly increase the likelihood of attrition.

### 3️⃣ Career Growth Matters

Employees who don’t see career advancement opportunities tend to resign more frequently — especially in sales-related roles.

### 4️⃣ Salary Isn’t Everything

Although compensation is important, **a balanced work-life environment and recognition** play an even greater role in retention.

---

## 🧾 Conclusion

> The “typical employee” who leaves is:
> An experienced professional who is dissatisfied with their job or environment, feels career stagnation, and frequently works overtime.

This analysis emphasizes that **employee retention strategies must go beyond salary hikes** — focusing instead on improving satisfaction, growth, and work-life balance.

---

## 🚀 Future Enhancements

🔹 Apply hyperparameter tuning to improve logistic regression performance
🔹 Add interactive dashboards for HR visualization
🔹 Incorporate additional factors like training data and engagement scores
🔹 Compare logistic regression results with ensemble models (Random Forest, XGBoost) in future iterations

---

## 📁 Project Structure

```
📦 Employee_Attrition_Prediction/
 ┣ 📄 HR-Employee-Attrition.csv
 ┣ 📓 Employee_Attrition_Prediction.ipynb
 ┣ 📜 README.md
```

---

## 🧰 How to Run

1️⃣ Clone the repository:

```bash
git clone https://github.com/yourusername/Employee-Attrition-Prediction.git
```

2️⃣ Install dependencies:

```bash
pip install -r requirements.txt
```

3️⃣ Open and run the notebook:

```bash
jupyter notebook Employee_Attrition_Prediction.ipynb
```

---

## 🙌 Acknowledgement

Special thanks to **HexSoftwares Company** for providing mentorship and guidance throughout this internship project.

---
