****AI Resume Screening using Machine Learning****

****Project Overview****

This project implements a machine learning-based resume screening system that helps automate the candidate selection process. The system analyzes candidate information such as education, experience, skills, certifications, projects, and AI score to predict whether a candidate should be hired or rejected.
The goal of this project is to demonstrate how machine learning models can assist recruiters in filtering resumes efficiently.


****Dataset****

The dataset used in this project is AI Resume Screening Dataset containing 1000 candidate records with multiple features describing candidate qualifications.

****Dataset Features****

1. Education
2. Skills
3. Experience (Years)
4. Certifications
5. Projects Count
6. Salary Expectation
7. Job Role
8. AI Score
9. Recruiter Decision (Target Variable)

**Target Variable**

Recruiter Decision
0 → Reject
1 → Hire


****Machine Learning Models Implemented****

The following classification algorithms were implemented and compared:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine (SVM)
5. K-Nearest Neighbors (KNN)
6. Gradient Boosting / XGBoost
These models were evaluated to determine which algorithm performs best for resume screening prediction.


****Project Workflow****

The project follows the standard machine learning pipeline:

1. Data Collection
2. Data Preprocessing
3. Feature Encoding
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Prediction


****Technologies Used****

1. Python
2. Pandas
3. NumPy
4. Scikit-learn
5. Matplotlib
6. Seaborn
7. Jupyter Notebook


****Model Evaluation Metrics****

The models were evaluated using:

1. Accuracy
2. Precision
3. Recall
4. F1 Score
5. Confusion Matrix
These metrics help measure how well the models classify resumes.


****Feature Importance****

Using ensemble models such as Random Forest, the system identifies the most important features influencing recruiter decisions such as:
1. AI Score
2. Experience
3. Projects
4. Skills
