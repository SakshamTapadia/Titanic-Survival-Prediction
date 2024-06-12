# Titanic Survival Prediction

## Project Overview

This project aims to predict the survival outcomes of passengers aboard the Titanic using machine learning techniques. The dataset for this project includes various features such as passenger class, gender, age, fare, and more. By analyzing these features, we can build a predictive model to estimate the likelihood of survival for each passenger.

## Dataset

The dataset used in this project can be found [here](https://github.com/SakshamTapadia/CODSOFT/blob/main/Task1%20-%20DataSet.csv). It contains the following columns:

- **PassengerId**: Unique ID for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard the Titanic
- **Parch**: Number of parents/children aboard the Titanic
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Notebook

The complete project notebook is available [here](https://github.com/SakshamTapadia/CODSOFT/blob/main/Task1%20-Titanic%20Survival%20Prediction.ipynb). It includes the following steps:

1. **Data Exploration and Preprocessing**: 
    - Load and inspect the dataset.
    - Handle missing values.
    - Encode categorical variables.
    - Feature engineering.
  
2. **Exploratory Data Analysis (EDA)**: 
    - Visualize the distribution of features.
    - Analyze the correlation between features and survival.

3. **Model Building**: 
    - Split the data into training and testing sets.
    - Train multiple machine learning models (e.g., Logistic Regression, Decision Tree, Random Forest).
    - Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

4. **Model Evaluation and Selection**: 
    - Compare the performance of different models.
    - Select the best model based on evaluation metrics.
  
5. **Prediction and Conclusion**: 
    - Make predictions on the test set.
    - Summarize the findings and conclusion.

## Results

The results of the model evaluation and the final predictions on the test set are included in the project notebook. The best-performing model achieved a high accuracy and provided insights into the most important features influencing survival.

## Conclusion

This project demonstrates the application of machine learning techniques to predict survival outcomes on the Titanic dataset. By leveraging data preprocessing, exploratory data analysis, and model evaluation, we can gain valuable insights and build accurate predictive models.
