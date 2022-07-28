# Label-detection
Detect if label belongs to class 0 or 1 using machine learning predictive algorithms

**Notebook should contain :**
1. EDA, Feature selection, preprocessing
2. Model performance analysis in terms of validation and risks involved
3. model predictions for test dataset
4. write the dependencies, libraries in seperate python file
5. Readme file - approach to solve prob, thought process

**Task steps:**
1. Split the train set into train and validation in 4:1 ratio
2. Explain model selection. Apply classification model 
3. Evaluate model accuracy

## Approach:

Notebook 1 (Predictive model pipeline): 

1. Load and split the data 

2. Standardize and Pipeline tree-based algorithms to handle data imbalances

3. Obtain algorithms with highest accuracy

4. Tune the algorithm and find best parameters

Notebook 2 (Label detection Predictive Analytics) :

1. Explore the dataset 
    - Check data relations
    - Data correlations
    - Missing values
    - Outliers
    - Different data types
    - Fix data distribution skewness, kurtosis
    - Fix outliers
    - Scale, undersample the data
    
2. Split the cleaned data into 3 sets ( Test, Train, validation set)

3. Utilise 5 fold validation and compare accuracy / recall / roc-auc scores for train, test and validation sets 

4. Take the parameters and model from notebook1. Integrate data with this model.

5. Plot confusion matrix, roc-auc curves and expected-actual prediction
