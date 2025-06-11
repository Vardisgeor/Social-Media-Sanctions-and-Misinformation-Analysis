
# Social Media Analysis – Twitter Suspensions After the 2020 Election

## Description

This Jupyter Notebook explores **Twitter user suspensions** after the 2020 U.S. elections, focusing on the relationship between user behavior, low-quality news sharing, and political ideology. The analysis uses statistical modeling (Probit/Logit), PCA, and hypothesis testing.

**Author**: Vardis Georgilas

## Files Needed

* `mosleh_et_al_data.csv` – Must be in the **same directory** as the notebook.

## 🧪 Contents

* 📊 Relative frequency distributions of low-quality content
* 🧠 Crowdsourced identification of low-quality sharing
* 📈 t-tests and regression models
* 🧬 PCA for harmful language variables
* 🧮 Probit and Logit models to predict suspension
* ✅ Bonferroni and Holm-Bonferroni corrections
* 🇬🇷 Σχολιασμός και συμπεράσματα στα ελληνικά


## 🧪 What We Did

### 1. Data Loading & Cleaning

* Load `mosleh_et_al_data.csv` using `pandas`.
* Clean and prepare variables for modeling (e.g., ideology, suspension status, misinformation indicators).

### 2. Exploratory Analysis

* Visualize the **distribution of low-quality news sharing**.
* Compare **suspended vs non-suspended users** using descriptive stats.
* Explore correlation with **political ideology**.

### 3. Statistical Testing

* Conduct **t-tests** to compare groups on various behavioral metrics.
* Apply **Bonferroni and Holm-Bonferroni corrections** to control false discovery rate.

### 4. Principal Component Analysis (PCA)

* Perform PCA on "harmful language" variables.
* Interpret first principal component and its correlation with suspension.

### 5. Predictive Modeling

* Fit **Probit** and **Logit** models to predict suspension likelihood.
* Use:

  * Single predictors (e.g., ideology, misinformation sharing).
  * Multiple predictors in combined models.
* Compare predictive power and interpret coefficients.

### 6. Interpretation & Discussion

* Present **key insights** in markdown (in Greek).
* Discuss the difference in outcomes before and after multiple testing corrections.
* Compare the explanatory strength of Probit vs Logit models.


## Run Instructions

1. Place `mosleh_et_al_data.csv` in the same folder.
2. Open the notebook in Jupyter or VS Code.
3. Run all cells.

