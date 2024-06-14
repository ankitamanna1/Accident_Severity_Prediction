# Prediction Of Accident Severity 
### Project Overview

 Now a days Insurance companies are using data-driven decisions and machine learning models to optimise
 all business areas to increase their profit. Claim payments are major cost and unpaid claims are largest
 liabilities.To optimise the process and increase their profit margin by setteling the proper insurance premium
 amount by assesing the risk profile of insurence claimer. Informations relating to car, Driver, Driver area,
 Journey purpose of driver, vehicle conditins help to identify the risk associated with insuring the particular
 driver or car. By proper analysing the data they can predict likelihood of accidents and severity.

 
 ### Data Source
 https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data

 ### Steps Include:
 
- **Data cleaning:**
  
    -  Data loading and checking
    -  Handling Missing Values
    -  Cleaning and merge the relevant files
    -  Data cleaning and formatting


- **Exploratory Data Analysis**
    -  Checked Trend
    -  Distribution
    -  Correlation Matrics

- **Outliers handlings and Feature selection**

- **Applying ML**
  
    - Splitting the dataset into trainset and testset
    - Feature engineering and applied SMOTE for class imbalance    
    - Applied Maching Learning models (Decision Tree, XG Boost, Random Forest, SVM, ADABoost)  
    - Hyperparameter Tuning of models using Grid search and estimated best hyperparameter    
    - Compared the model outcomes and choose the model with best performance

### Main Findings:
 I trained my training dataset to 4 different models:
- **ADA boost** model outperformed the other models for the given dataset
- I tried to take account of actual occurance of each classes.
 My model is able to predict 1 fatal,30 serious,1488 slight true positive case based on driver's and
 vehicle history.
- Based on the prediction the insurance company will be able to predict the premium range based on
  predicted severity and increase revenue.
 Though Road condition, Time, no of casualties these would helpful to better prediction,As a business
 analyst team from a insurance company, these conditions will not be availabe at the time of predicting
 premium.
