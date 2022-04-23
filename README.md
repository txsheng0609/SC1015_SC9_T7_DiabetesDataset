# SC1015 Data Science Project: Factors Affecting Diabetes

![Cover page](https://user-images.githubusercontent.com/104262490/164896985-715b7df6-a1da-4f61-86e4-5b50d9f3d8c6.png)

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on one of the most prevalent chronic diseases, **Diabetes**. For detailed walkthrough, please view the source code in order here (#Setup-and-Process):

## Problem Defination
Diabetes is a chronic disease that occurs either when the pancreas does not produce enough insulin or when the body cannot effectively use the insulin it produces. Having diabetes also increases the risk of many complications such as cardiovascular disease and kidney damage. Detecting diabetes early can help pave the way for effective treatment, highlighting the importance of knowing what factors are strongly associated with diabetes. Hence, predictive models for diabetes risk are important tools for the public and public health officials. This leads us to our problem question: 

**"What are the most important factors in predicting whether a person has diabetes?"**
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
- Explored the distribution of each variables  

Multivariate  
- Explored relationship of each variables vs `Diabetes`
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

## 9. Contributors


## References
