##Heart Disease Prediction

Introduction
This machine learning project aims to predict the presence of heart disease in individuals using various medical attributes. The dataset used in this project is sourced from Kaggle.

Project Goal
The primary goal of this project is to develop a machine learning model that can accurately predict whether a person has heart disease based on their medical data.

Dataset
The dataset consists of 303 observations with 14 attributes:

age: Age of the individual
sex: Gender (1 = male; 0 = female)
cp: Chest pain type (0-3)
trestbps: Resting blood pressure (in mm Hg)
chol: Serum cholesterol in mg/dl
fbs: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
restecg: Resting electrocardiographic results (0-2)
thalach: Maximum heart rate achieved
exang: Exercise induced angina (1 = yes; 0 = no)
oldpeak: ST depression induced by exercise relative to rest
slope: The slope of the peak exercise ST segment (0-2)
ca: Number of major vessels (0-3) colored by fluoroscopy
thal: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)
target: Presence of heart disease (1 = presence; 0 = absence)
Project Workflow
Data Exploration and Visualization:

Understanding the distribution of data
Visualizing the correlation between features using a heatmap
Checking for class imbalance in the target variable
Data Processing:

Converting categorical variables into dummy variables using pd.get_dummies
Scaling numerical features using StandardScaler
Model Development:

Experimenting with three different machine learning algorithms:
K-Nearest Neighbors (KNeighborsClassifier)
Decision Tree (DecisionTreeClassifier)
Random Forest (RandomForestClassifier)
Splitting the dataset into training and testing sets using train_test_split
Training and evaluating models
Model Evaluation:

Evaluating the performance of each model using accuracy, precision, recall, and F1-score
Comparing the results to select the best performing model
Model Details
K-Nearest Neighbors: A simple algorithm that stores all available cases and classifies new cases based on a similarity measure.
Decision Tree: A non-parametric supervised learning method used for classification and regression.
Random Forest: An ensemble method that constructs multiple decision trees and merges them together to get a more accurate and stable prediction.
Results
The performance of each model is evaluated and compared.
Visualizations such as confusion matrices and ROC curves are used to illustrate the results.
Key Takeaways
The importance of data preprocessing steps like handling categorical variables and scaling.
Comparative analysis of different machine learning algorithms.
Insights into the feature importance and their impact on predicting heart disease.
Conclusion
This project demonstrates the application of machine learning techniques to predict heart disease. By experimenting with different models and evaluating their performance, we can gain insights into the most effective approaches for this type of medical data.
