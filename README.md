# Heart Disease Prediction Using Machine Learning

## 1. Project Overview
This project aims to create a robust predictive model capable of predicting the existence of heart disease based on personal key indicators, enabling healthcare professionals to make informed decisions, facilitate early intervention, and improve patient outcomes by identifying high-risk individuals.

## 2. Dataset Description
The dataset consists of features related to an individual's lifestyle, health conditions, demographic information and general well-being of each individual. These variables serve as key indicators that can potentially influence the prediction of heart disease, allowing for a comprehensive analysis of both medical and behavioral factors.. Below is an overview of the key columns present in the dataset:

- **Target Variable**:
  - `HeartDisease`: This is the target variable for our prediction model, which represents the existence of heart disease.

- **Features**:
  -  `BMI`: The individual's Body Mass Index (BMI), a measure of body fat based on height and weight.
  -  `Smoking`: Indicates whether the individual smokes (Yes or No).
  -  `AlcoholDrinking`: Indicates whether the individual consumes alcohol frequently (Yes or No).
  -  `Stroke`: Indicates whether the individual has experienced a stroke (Yes or No).
  -  `PhysicalHealth`: The number of days in the past 30 days that the individual experienced poor physical health.
  -  `MentalHealth`: The number of days in the past 30 days that the individual experienced poor mental health.
  -  `DiffWalking`: Indicates whether the individual has difficulty walking or climbing stairs (Yes or No).
  -  `Sex`: The biological sex of the individual (Male or Female).
  -  `AgeCategory`: The age range of the individual (categorized into specific age groups).
  -  `Race`: The self-reported race of the individual.
  -  `Diabetic`: Indicates whether the individual has diabetes (Yes or No).
  -  `PhysicalActivity`: Indicates whether the individual engages in regular physical activity (Yes or No).
  -  `GenHealth`: The individual's self-assessed general health status (Excellent, Very Good, Good, Fair, Poor).
  -  `SleepTime`: The average number of hours of sleep the individual gets per day.
  -  `Asthma`: Indicates whether the individual has asthma (Yes or No).
  -  `KidneyDisease`: Indicates whether the individual has kidney disease (Yes or No).
  -  `SkinCancer`: Indicates whether the individual has been diagnosed with skin cancer (Yes or No).

## 3. Project Structure
**Data**
- HeartDisease.csv              (Raw dataset)
- heart_model.csv                       (Preprocessed dataset used for training)

**Notebook**
- HeartDiseasePrediction_FarzanaSyakira.ipynb  (Notebook containing all steps)

## 4. Results
The algorithms used in this project are Decision Tree, Random Forest and Naive Bayes. The Random Forest model demonstrates strong performance as the best choice for prediction, boasting a high accuracy of 90.10%.

## 7. Conclusion and Future Work
Given these insights, the Random Forest model stands out as the most reliable option for predicting outcomes, although further enhancements through techniques such as ensemble methods, resampling strategies, and hyperparameter tuning may be explored to refine its performance even further.
