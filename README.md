# SC1015 Data Science Project: Factors Affecting Diabetes
![COVERRRR](https://user-images.githubusercontent.com/104262490/164909829-55d3c276-c0ce-42ca-809a-feec9e914ae6.png)

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on one of the most prevalent chronic diseases, **Diabetes**. For detailed walkthrough, please refer to [Setup and Process](#setup-and-process).

## Problem Definition
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

## Setup and Process
### 1. Data Collection
Dataset (Kaggle): https://www.kaggle.com/alexteboul/diabetes-health-indicators-dataset-notebook  
Data Dictionary: https://www.cdc.gov/brfss/annual_data/2015/pdf/codebook15_llcp.pdf
### 2. Data Cleaning and Preparation
- Renamed binary data
- Splitted dataset into 80% for training and 20% for testing
- Normalisation not required since the dataset from Kaggle has been normalised
### 3. Exploratory Data Analysis
Univariate  
- Explored the distribution of each variables  

Multivariate  
- Explored relationship of each variables vs `Diabetes`  

Removed Outliers Based on `BMI`

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
![LEArnin](https://user-images.githubusercontent.com/104262490/164909807-22e56801-44bf-4f90-b2e5-02b969f4be39.png)

Lastly, we would like to point out that this dataset includes surveyees who ever had Type 1 OR Type 2 diabetes which may affect the accuracy and reliability of our findings. Taking this into consideration, we should not therefore rely entirely on the few factors mentioned as the only guide to prevent diabetes.

## Contributors
* Teoh Xi Sheng - Exploratory Data Analysis, Data Resampling, Data Extraction
* Chew Zhi Yi Mark - Random Forest, Decision Tree, Gradient Boosting 
* Janelle Koh Wei Shan - Data Visualization, Overall Presentation

## References
- https://www.statology.org/interpret-cramers-v/
- https://towardsdatascience.com/all-machine-learning-models-explained-in-6-minutes-9fe30ff6776a
- https://www.kaggle.com/alexteboul/diabetes-health-indicators-dataset-notebook  
- https://www.cdc.gov/brfss/annual_data/2015/pdf/codebook15_llcp.pdf
- https://www.datasciencecentral.com/decision-tree-vs-random-forest-vs-boosted-trees-explained/
- https://slidesgo.com/theme/diabetes-infographics#search-diabetes&position-1&results-4
