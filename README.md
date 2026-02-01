Student Marks Predictors by using Simple Linear Regression

1. Project Title
Project Name: Student Marks Prediction using Simple Linear Regression

2. Problem Statement
   
Problem Description
- Many students struggle to pass exams due to insufficient study time. This project aims to predict whether a student will get intended marks based on their study hours

- Motivation
Early prediction of student performance can help educators identify at-risk students and provide timely intervention.
Machine learning is suitable for this task as it can learn patterns from historical data and make
predictions on new data.

- Objectives
To build a simple machine learning model to predict student pass/fail outcomes
To understand the supervised learning workflow
To evaluate model performance using accuracy

3. Domain Understanding
The education domain focuses on improving student performance and learning outcomes. Key factors influencing academic success include study habits, attendance, and engagement.
Traditional evaluation methods are reactive, while predictive models can provide proactive insights.

4. ML Problem Formulation
Type of ML Problem: Simple Linear Regression - Supervised Learning
Input Features (X): Hours
Target Variable (y): Predicted Marks
Assumptions: Higher study hours increase the likelihood of passing marks way higher
Success Metrics: Accuracy = Regression Score Function: 95%

5. Data Collection
Data Sources : https://raw.githubusercontent.com/masturina9/My_Datasets/refs/heads/main/Student_Grades.csv
The dataset was manually created for educational purposes.
Dataset Overview
Number of records: 24
Number of features: 1 input features, 1 target variable
Data format: CSV

6. Exploratory Data Analysis (EDA)
- Students with higher study hours tend to pass
- No missing values were found

7. Data Cleaning & Preprocessing
- Verified no missing values
- Selected relevant numerical features
- Split data into training and testing sets (80/20)

8. Feature Engineering
No additional feature engineering was performed to keep the model simple and interpretable.

9. Baseline Model
A Simple Linear Regression model was used as the baseline model due to its simplicity and effectiveness for binary classification problems.

10. Advanced Modeling & Model Selection
No advanced models were used. Simple Linear Regression was selected as the final model to maintain simplicity and clarity.

11. Model Evaluation
Metric Used: Accuracy
The model achieved an accuracy of 95% on the test dataset

12. Model Interpretability
Simple Linear Regression provides interpretable coefficients that show how study hours and score influence
the probability of passing.

13. Deployment Strategy (Conceptual)
The model can be deployed as a simple web application where educators input hours to receive marks predictions.

14. Results & Business Impact
The model demonstrates that basic academic indicators can be used to predict student marks performance.
This approach can assist educators in identifying students who may need additional support.

15. Limitations & Future Work
- Limitations
Small dataset size
Limited number of features

- Future Work
Collect real-world student data
Include additional features such as assignment scores

16. How to Run This Project
Google Colab link : https://colab.research.google.com/drive/1WVagY-87NiToaCK5oW5Wp1SCTEi45D9S?usp=sharing

17. Project Structure
project/
│
├── README.md
├── student_data.csv
├── StudentsMarksPredictions.ipynb

18. Final Note
This project demonstrates a complete end-to-end supervised learning workflow using a simple and interpretable machine learning model.

