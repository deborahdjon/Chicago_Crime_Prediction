# Chicago Crime Prediction
## Task
_Predict crime in the city of Chicago using real-world data and artificial intelligence._

## Approch
- Performing a comparative analysis on theft prediction using multiple models (KNN, Logistic Regression, Random Forest, Support Vector Machine, and XGBoost), all trained on a publicly available dataset hosted on https://catalog.data.gov/.

## Key Insights

### Dataset Imbalance
An exploratory analysis of the dataset revealed a high skew in the target variable distribution. To combat this and prevent model bias, we used SMOTE to balance the dataset and transformed the task into a binary classification problem, where we identify wether a crime is theft or not. 
 <img width="656" alt="image" src="https://github.com/deborahdjon/Chicago_Crime_Prediction/assets/118228430/7c61020a-83dd-4112-82af-8f03da5cc2d6">

## XGBoost wins

 


- Writing a research paper to summarise all findings, as well as to document the analysis, data transformation, and modelling phases that led to said findings.

- The paper was presented at the [SKILL 2023](https://skill.gi.de/) and won the Best Paper award. It is currently available [here](https://doi.org/10.48550/arXiv.2304.13464).
