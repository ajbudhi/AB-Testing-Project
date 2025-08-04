# AB Testing Project

### 📘 Overview

This project aims to analyze the results of an A/B test designed to measure the impact of displaying ads on user conversion behavior.

### 🔍 Objective

To determine whether exposing users to ads (ad group) leads to a higher conversion rate compared to showing public service announcements (psa group).


### 📊 Dataset Summary

- Users: 588,101
- Groups:
    - ad - 96% of users
    - PSA (control) - 4% of users
- Features:
    - converted - whether the user converted


### ✅ Results

- __Conversion Rate__: 
    - ad: 2.55%
    - psa: 1.79%
- __Z-Test__: Statistically significant difference (p < 0.00001)
- __Interpretation__: Ads were found to be more effective than PSA since it had higher conversion rate.

### ⚠️ Limitations

Through our Exploratory Data Analysis, we found that the dataset was severely imbalanced, with the majority of the data belongs to the Ad group compared to the PSA group. Ideally, we would want a balanced, 50/50 dataset. This imbalance could render the result to be less reliable, especially if there is hidden confounding.

### 📝 Further Analysis

- Investigate the reason for group imbalance
- Consider stratified re-sampling or bootstrapping to validate findings
- Analyze other features in the dataset that may affect the conversion rate, such as by Day of Most Ads or Hour of Most Ads

### 📁 Files

- __marketing_AB.csv__: Raw dataset
- __AB_testing.ipynb__: Jupyter Notebook of the project, containing Exploratory Data Analysis, Statistical Testing, and interpretation
- __README.md__: Project overview and documentation
