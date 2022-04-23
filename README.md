# SC1015 Data Science Project: Factors affecting Diabetes
## About
## Problem Defination
## Libraries and Models
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Pearson's Correlation Matrix (Numerical Varaibles)
- Cramer's V Correlation Matrix (Categorical Variables)
- Sklearn
- Decision Tree
- Random Forest
- Gradient Boosting
## Files
## Setup and Process
### 1. Data Collection
Dataset (Kaggle): https://www.kaggle.com/alexteboul/diabetes-health-indicators-dataset-notebook  
Data Dictionary: https://www.cdc.gov/brfss/annual_data/2015/pdf/codebook15_llcp.pdf
### 2. Data Cleaning and Preparation
- Renamed binary data
- Splitted dataset into 80% for training and 20% for testing
- Normalisation not required since the dataset from Kaggle has been normalised
### 3. Exploratary Data Analysis
Univariate
- Explored the distrribution of each variables
Multivariate
- Explored relationship of each variables vs `diabetes`
- Removed outliers based on `BMI`
### 4. Model Training
The following supervised classification machine learning models were trained on the train dataset:
- Decision Tree
- Random Forest
- Gradient Boosting
### 5. Model Evaluation on Test Dataset
The following metrics were used to evaluate the models
- Classification Accuracy
- True Positive Rate
- True Negative Rate
- False Positive Rate
- False Negative Rate  

The most important variables in each models were extracted using `Feature Importance` function
### 6. Model Re-training
The models were retrained using only the most important variables to reduce overfitting issues
### 7. Model Re-evaluation on Test Dataset
The same metrics were used to evaluate the performace of the new models
### 8. Insights and Conclusion
## References
