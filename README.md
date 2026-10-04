# 📐 Statistical Sampling Methods & Weight Calibration (Excel)

## 📌 Project Overview
This project focuses on **survey sampling methodology, sample design, and weight calibration** applied to a financial dataset (German Credit Data, N = 1,000). 

The primary objective was to evaluate different probability sampling schemes, calculate domain estimators (simple, ratio, regression), and implement weight adjustment techniques (calibration/raking) to mitigate non-response bias and estimation errors.

---

## 🛠️ Key Methodologies & Techniques Included

### 1. Simple Random Sampling (SRS)
* **With/Without Replacement:** Estimation of total and mean loan duration.
* **Complex Estimators:** Simple, Ratio, and Regression estimators evaluated against margin of error ($d \le 2$ months).
* **Fraction Estimation:** Proportion of "good" vs "bad" credit risks.

### 2. Stratified Sampling (Warstwowe)
* **Allocation Strategies:** Proportional, Equal, and **Neyman Optimal Allocation**.
* **Post-stratification:** Adjusting weights post-data collection based on demographic strata (Gender & Credit Class).

### 3. Cluster Sampling (Zespołowe)
* Single-stage cluster sampling with equal and unequal cluster sizes based on age groups.

### 4. Non-Response Bias & Weight Calibration (Kalibracja Wag)
* **InfoS Calibration:** Adjusting sample weights when partial non-response occurs.
* **Raking (Iterative Proportional Fitting):** Calibrating weights across marginal population distributions (Housing vs Demographics).

---

## 📂 File Structure
* 📊 **`project_git.xlsx`** – Comprehensive Excel workbook containing 24 sheet models with step-by-step mathematical calculations, formulas, and sampling simulations.

---

## 🧰 Tools & Skills Applied
* **Microsoft Excel:** Complex statistical formulas, array operations, dynamic weighting tables.
* **Statistical Theory:** Survey Methodology, Sample Size Determination, Margin of Error Calculation, Weight Calibration / Raking.
