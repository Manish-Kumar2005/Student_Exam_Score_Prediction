#  Student Exam Score Prediction

This project is part of my internship, where I aimed to predict students' exam scores using features such as:

- Hours Studied  
- Previous Exam Scores  
- Attendance Percentage  

I used different regression models to estimate a student's score and identify which factors affect performance the most.


## Dataset

A synthetic dataset of 200 students was created, with the following columns:

- `Hours_Studied`
- `Previous_Score`
- `Attendance`
- `Exam_Score` (Target)

**Dataset Used:** `student_exam_scores_dataset.csv`


## Regression Models Used

- **Linear Regression**
- **Random Forest Regressor**
- **Support Vector Regressor (SVR)**


## Model Evaluation

Each model was evaluated using:
- **R² Score**
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**

## Conclusion

After testing all models, **Linear Regression performed the best** with the highest R² score and lowest error values.  
It showed that the relationship between input features and exam scores is mostly linear.

**Best Model: Linear Regression**  
 
 - Simple, effective, and accurate for this dataset.

## Tools Used

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn


##  References:
- [Kaggle Dataset (for inspiration)](https://www.kaggle.com/datasets/impapan/student-performance-data-set)
