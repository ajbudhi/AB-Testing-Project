# AB Testing Project

### Overview

This project aims to analyze the results of an A/B test designed to measure the impact of displaying ads on user conversion behavior.

### 🔍 Objective

To determine whether exposing users to ads (ad group) leads to a higher conversion rate compared to showing public service announcements (psa group).

### Dataset Summary



### Limitations

Through our Exploratory Data Analysis, we found that the dataset was severely imbalaned, with the majority of the data belongs to the Ad group compared to the PSA group. Ideally, we would want a balanced, 50/50 dataset. This imbalance could render the result to be less reliable, especially if there is hidden confounding.

### Further Analysis

- Investigate the reason for group imbalance
- Consider stratified re-sampling or bootstrapping to validate findings
- Analyze other features in the dataset that may affect the conversion rate, such as by Day of Most Ads or Hour of Most Ads