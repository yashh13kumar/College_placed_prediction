# College Placed Prediction

## Project Overview
The College Placed Prediction project uses a machine learning model to predict whether a student is likely to get placed based on several features like age, gender, stream, CGPA, internship experience, hostel stay, and history of backlogs. The project utilizes Python and several machine learning models, such as Logistic Regression, Random Forest Classifier, and Support Vector Classifier (SVC), to analyze and predict placement outcomes.

## Dataset
The dataset used in this project contains information about students with the following attributes:
- Age: Age of the student.
- Gender: Gender of the student (encoded as Male = 1, Female = 0).
- Stream: Field of study of the student (e.g., Computer, Electronics, Mechanical, etc., encoded as numerical values).
- Internships: Number of internships completed by the student.
- CGPA: Cumulative Grade Point Average of the student.
- Hostel: Whether the student stayed in a hostel (Yes = 1, No = 0).
- History of Backlogs: Whether the student had any backlogs (Yes = 1, No = 0).
- PlacedOrNot: The target variable indicating whether the student got placed (1 for placed, 0 for not placed).

## Objectives
The primary objective of this project is to build and compare different machine learning models to predict whether a student gets placed. The models used include:
- Logistic Regression
- Random Forest Classifier
- Support Vector Classifier (SVC)

## Tools and Libraries Used
- Python: Programming language
- Pandas: Data manipulation and analysis
- Scikit-learn: Machine learning library for model training and evaluation
- Numpy: Numerical computing library

## Project Workflow
1. Data Preprocessing:
   - Encoding categorical variables such as `Gender` and `Stream`.
   - Splitting the dataset into training and testing sets.

2. Model Training and Evaluation:
   - Train a Logistic Regression model and evaluate its accuracy.
   - Train a Random Forest Classifier and evaluate its accuracy.
   - Train a Support Vector Classifier (SVC) and evaluate its accuracy.
   - Compare the performance of the three models.

3. Prediction for New Examples:
   - Create example data to test the model’s prediction.
   - Predict whether a new student profile will get placed or not.


## Example Predictions
The project includes sample predictions to demonstrate the model’s behavior:
- Example of a Student Likely to be Placed: A student with a good CGPA, completed internships, and no history of backlogs.
- Example of a Student Not Likely to be Placed: A student with a low CGPA, no internships, and a history of backlogs.

## Conclusion
This project demonstrates the use of machine learning models to predict college placements based on a variety of student attributes. The predictions can be valuable for identifying factors that contribute to successful placements and for guiding students to improve their profiles for better placement opportunities.

