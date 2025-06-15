# Goal
The goal is to make a linear regression model calculating performance of a student from multiple variables
It is done for the purpose of learning linear regression models.

# Informations on the Dataset
The Student Performance Dataset is a dataset designed to examine the factors influencing academic student performance. The dataset consists of 10,000 student records, with each record containing information about various predictors and a performance index.

Using a dataset from kaggle
https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression

### Variables:
* **Hours Studied**: The total number of hours spent studying by each student.
* **Previous Scores**: The scores obtained by students in previous tests.
* **Extracurricular Activities**: Whether the student participates in extracurricular activities (Yes or No).
* **Sleep Hours**: The average number of hours of sleep the student had per day.
* **Sample Question Papers Practiced**: The number of sample question papers the student practiced.

### Target Variable:
* **Performance Index**: A measure of the overall performance of each student. The performance index represents the student's academic performance and has been rounded to the nearest integer. The index ranges from 10 to 100, with higher values indicating better performance.

# Model Evaluation
R2 Score:  98.90110607021137
Mean Absolute Error:  1.6090437564045221
Mean Squared Error:  4.066563824092681
RMSE:  2.0165722957763457

Equation of the multiple linear regression model is :
2.85 × Hours Studied + 1.02 × Previous Scores + 0.61 × Extracurricular Activities + 0.48 × Sleep Hours + 0.19 × Sample Question Papers Practiced - 33.92
