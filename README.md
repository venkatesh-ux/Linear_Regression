# Jamboree Admission Predictor
This project predicts the likelihood of admission to graduate programs using machine learning techniques. The dataset consists of various academic and profile-related features, and the target variable is the "Chance of Admit" (ranging from 0 to 1). The model employs linear regression and regularization techniques like Lasso and Ridge to enhance prediction accuracy.

# Dataset Features
Serial No.: Unique identifier for each applicant.
GRE Scores: Graduate Record Examination scores (out of 340).
TOEFL Scores: Test of English as a Foreign Language scores (out of 120).
University Rating: A rating of the university (out of 5).
SOP Strength: Statement of Purpose strength (out of 5).
LOR Strength: Letter of Recommendation strength (out of 5).
Undergraduate GPA: Grade Point Average in undergraduate studies (out of 10).
Research Experience: Binary value indicating research experience (0 = No, 1 = Yes).
Chance of Admit: Probability of admission (target variable, ranging from 0 to 1).
# Project Highlights
Linear Regression: Implemented as a baseline predictive model.
Regularization Techniques:
Lasso Regression: To penalize less important features and enhance generalization.
Ridge Regression: To handle multicollinearity and reduce overfitting.
Evaluation Metrics: Used metrics like Mean Squared Error (MSE) and R² Score to evaluate model performance.
Data Preprocessing: Included handling missing values, scaling features, and exploratory data analysis to understand feature relationships.
# Tools and Libraries
Python: Core programming language used.
Libraries:
pandas for data manipulation.
NumPy for numerical operations.
Matplotlib and seaborn for visualization.
scikit-learn for model building and evaluation.
# Conclusion
The project demonstrates the application of regression and regularization techniques to predict admission chances effectively. The use of Lasso and Ridge regularization helped improve model robustness and interpretability.
