# Boosting Project

## Project Overview

In this project, census data from the UCI Machine Learning Repository is used to predict whether an individual earns more than $50,000 annually. Boosting algorithms are employed to enhance prediction accuracy. The main tasks include data preprocessing, model training using boosting techniques, and evaluating the model's performance.

## Data Description

The dataset includes various features and a target variable (`income`). Some key features are:

- **age**: continuous
- **workclass**: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked
- **education**: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool
- **race**: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black
- **sex**: Female, Male
- **capital-gain**: continuous
- **capital-loss**: continuous
- **hours-per-week**: continuous
- **native country**: discrete
- **income**: discrete, >50K, <=50K

## Project Steps

1. **Data Loading**:
   - Load the dataset into a DataFrame named `df`.

2. **Data Preprocessing**:
   - Handle any missing values.
   - Encode categorical variables using appropriate encoding techniques.
   - Split the dataset into training and testing sets.

3. **Model Training**:
   - Implement boosting algorithms using scikit-learn (e.g., AdaBoost, Gradient Boosting).
   - Train the models on the training data.

4. **Model Evaluation**:
   - Evaluate the performance of the models using metrics such as accuracy, precision, recall, and F1-score.
   - Analyze the results to determine the effectiveness of boosting in predicting income levels.

## Conclusion

This project demonstrates the use of boosting algorithms to predict whether an individual earns more than $50,000 based on census data. Through data preprocessing, model training, and evaluation, the project provides insights into the performance of boosting techniques in classification tasks.

## Outputs

![image](https://github.com/user-attachments/assets/e5947586-c88f-416f-b96b-d2133eab70d2)

![image](https://github.com/user-attachments/assets/476aa537-1fab-4461-9380-9575647c5d5b)


