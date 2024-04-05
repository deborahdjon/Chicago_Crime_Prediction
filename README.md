# Chicago Crime Prediction

## Task
Predict crime in the city of Chicago using real-world data and artificial intelligence.

## Dataset
The dataset was a public dataset from the US government and contained 7,724,493 records, amounting to 1.17 GB of data. It includes 22 features.

## Approach
We performed a comparative analysis on theft prediction using multiple models: KNN, Logistic Regression, Random Forest, Support Vector Machine, and XGBoost. All models were trained on a publicly available dataset hosted on [catalog.data.gov](https://catalog.data.gov/).

## Key Insights

### Dataset Imbalance
An exploratory analysis of the dataset revealed a significant skew in the distribution of the target variable. To combat this and prevent model bias, we used SMOTE to balance the dataset and transformed the task into a binary classification problem, where we identify whether a crime is theft or not. 

![Dataset Imbalance Correction](https://github.com/deborahdjon/Chicago_Crime_Prediction/assets/118228430/7c61020a-83dd-4112-82af-8f03da5cc2d6)

## Feature Contributions
Features used for modeling included:
- Domestic (binary variable)
- Block (location)
- Location description (e.g., street, storefront)
- Weekday

Due to high Variance Inflation Factors (VIFs) and correlation measures, several variables were discarded in the feature engineering step.

Inspecting the feature importance scores in the figure below shows that different models have a different feature importance distribution.

![Feature Importance](https://github.com/deborahdjon/Chicago_Crime_Prediction/assets/118228430/6b164a7e-9355-482e-835c-5f2c7f7dffed)

## XGBoost Wins
Out of all considered algorithms, XGBoost performed best in classifying a crime as Theft or not theft.

![XGBoost Performance](https://github.com/deborahdjon/Chicago_Crime_Prediction/assets/118228430/a426a688-8b32-4b55-b9da-bfc43b3fc0a1)

- Writing a research paper to summarize all findings, as well as to document the analysis, data transformation, and modeling phases that led to said findings.

- The paper was presented at [SKILL 2023](https://skill.gi.de/) and won the Best Paper award. It is currently available [here](https://doi.org/10.48550/arXiv.2304.13464).
