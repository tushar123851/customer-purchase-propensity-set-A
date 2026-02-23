## 📊 Exploratory Data Analysis (EDA) – Visual Results

This folder contains all visualizations generated during data preprocessing and feature engineering.
The graphs illustrate data behavior before and after missing value treatment, helping to validate preprocessing decisions.

Each section is organized step-by-step, following standard data science EDA workflows.

--------------------------------

## 🔹 Univariate Analysis (Before Filling Missing Values)

📂 Folder: Before_filling_univariate_analysis

This section shows the distribution of individual variables before handling missing values.

--------------------------------

## 📌 Purpose

Identify missing values

Detect skewness

Spot extreme outliers

--------------------------------

## 📊 Visuals Included

Histograms

Boxplots

--------------------------------

## 🖼️ Graphs

These plots show the data condition **before handling missing values**.

### annual_income (Before Filling)
![annual_income Missing Before](Before_filling_univariate_analysis/annual_income.png)

### loyalty_score (Before Filling)
![loyalty_score Missing Before](Before_filling_univariate_analysis/loyaslty_score.png)

### price (Before Filling)
![price Missing Before](Before_filling_univariate_analysis/price.png)

### rating (Before Filling)
![rating Missing Before](Before_filling_univariate_analysis/rating.png)

---

## 🔹 Univariate Analysis (After Filling Missing Values)

📂 Folder: after_filling_univariate_analysis

These graphs demonstrate how distributions improve after imputation.

--------------------------------

## 📌 Purpose

Validate imputation strategy

Ensure stable distributions

--------------------------------

## 📊 Visuals Included

Histograms

Boxplots

--------------------------------

## 🖼️ Graphs

These plots show the data condition **after handling missing values**.

### annual_income (after Filling)
![annual_income Missing after](after_filling_univariate_analtysis/annual_income.png)

### loyalty_score (after Filling)
![loyalty_score Missing after](after_filling_univariate_analtysis/loyalty_score.png)

### price (after Filling)
![price Missing after](after_filling_univariate_analtysis/price.png)

### rating (after Filling)
![rating Missing after](after_filling_univariate_analtysis/rating.png)

### age (after Filling)
![age Missing after](after_filling_univariate_analtysis/age.png)

--------------------------------


## 🔹 Bivariate Analysis (Before Filling)

📂 Folder: before_filling_bivariate_analysis

Shows relationships between two variables before preprocessing.

--------------------------------

## 📌 Purpose

Identify missing-value impact

Observe raw correlations

--------------------------------

## 📊 Visuals Included

Scatter plots

Group comparisons

--------------------------------

## 🖼️ Graphs

Bivariate analysis shows **relationships between two variables**.


### age vs ratings
![age vs ratings](before_filling_bivariate_analysis/age_rating.png)

### annual_income vs purchased
![annual_income vs purchased](before_filling_bivariate_analysis/annnual_income_purchased.png)

### annual_income vs price
![annual_income vs price](before_filling_bivariate_analysis/annual_income_price.png)

--------------------------------

## 🔹 Bivariate Analysis (After Filling)

📂 Folder: bivariate_analysis_after_filling

Demonstrates cleaner and more meaningful relationships after preprocessing.

--------------------------------
 
## 📌 Purpose

Validate missing value treatment

Improve interpretability

--------------------------------

## 📊 Visuals Included

Scatter plots

Category vs numerical plots

--------------------------------

## 🖼️ Graphs


--------------------------------


## 🔹 Multivariate Analysis (Before Filling)

📂 Folder: before_filling_multivariate_analysis

Shows complex relationships between multiple variables before cleaning.

--------------------------------

## 📌 Purpose

Detect noise

Identify correlation distortion

--------------------------------

## 📊 Visuals Included

Correlation heatmaps

Multi-feature plots

--------------------------------

## 🖼️ Graphs

multivariate analysis shows **relationships between two and more than variables**.


### Heatmap
![Heatmap](before_filling_multivariate_analysis/heatmap.png)

### annual_income vs purchased vs age
![annual_income vs purchased vs age](before_filling_multivariate_analysis/age_income_purchased.png)

### price vs category vs purchased
![price vs category vs purchased](before_filling_multivariate_analysis/price_category_purchassed.png)


--------------------------------

## 🔹 Multivariate Analysis (After Filling)

📂 Folder: multivariate_analysis_after_filling

Final multivariate visualizations using cleaned and feature-engineered data.

--------------------------------

## 📌 Purpose

Confirm data readiness for ML

Validate feature relationships

--------------------------------

## 📊 Visuals Included

Correlation heatmaps

Feature interaction plots

--------------------------------
## 🖼️ Graphs

multivariate analysis shows **relationships between two and more than variables**.


### Heatmap
![Heatmap](multivariate analysis_after_filling/heatmap.png)

--------------------------------

## ✅ Key Insights from Visual Analysis

✔ Missing value treatment stabilized distributions

✔ Outliers were controlled effectively

✔ Feature relationships became clearer after preprocessing

✔ Data is now suitable for ML modeling
