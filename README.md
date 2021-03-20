![diabetes-word-cloud](https://user-images.githubusercontent.com/57557590/111818190-27704900-88f4-11eb-8e9b-ec84e2518a4d.jpg)

# Diabetes-Dataset-EDA-Building-Models-91-ROC
# Problem:
In this notebook, we want to predict if the patient has the disease (Diabetes) or not.
# Dataset:
The dataset comes from the Kaggle (The Biggest Data Science Community) https://www.kaggle.com/yashbansal1099/docspot
### There are 768 Rows and 9 Columns in the dataset.
### The dataset contains the following columns:

 * 0   Pregnancies               768 non-null    int64  
 * 1   Glucose                   768 non-null    int64  
 * 2   BloodPressure             768 non-null    int64  
 * 3   SkinThickness             768 non-null    int64  
 * 4   Insulin                   768 non-null    int64  
 * 5   BMI                       768 non-null    float64
 * 6   DiabetesPedigreeFunction  768 non-null    float64
 * 7   Age                       768 non-null    int64  
 * 8   Outcome                   768 non-null    int64
![33](https://user-images.githubusercontent.com/57557590/111818759-ca28c780-88f4-11eb-9cca-ead11541aca2.PNG)
# Exploratory Data Analysis EDA
* From the zero values, we can understand that they are Missing Values in our dataset
* Hnece, We would convert the Zero values into the NAN values and then solving the missing values
# Missing Values:
![Miss](https://user-images.githubusercontent.com/57557590/111877187-53083780-89b7-11eb-81ca-dcdd80bf39c9.PNG)
# Handling Missing Values
* Great approach for handling the missing values
# Outlier Detection:
![Outlier](https://user-images.githubusercontent.com/57557590/111877236-9793d300-89b7-11eb-8068-a0a7bfc0c6fa.PNG)
# Data Visualization:
* A comprehensive and informative data visualiztion was performed in this notebook 

![data vis](https://user-images.githubusercontent.com/57557590/111877308-fc4f2d80-89b7-11eb-9851-eddc9545ca2d.PNG)
# Correlation:
![corr](https://user-images.githubusercontent.com/57557590/111877372-57812000-89b8-11eb-8585-ef8630644fd5.PNG)

# Data Engineering
* New Feature
* Edit Feature
* Drop Feature
* Standardizing Data
