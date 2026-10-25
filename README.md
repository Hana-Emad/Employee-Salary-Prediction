# Employee-Salary-Prediction
### Employee Salary Prediction & Data Analysis Using Machine Learning

This project focuses on analyzing employee salary data and building machine learning regression models to predict **TotalPay** based on employee and compensation-related features.

The dataset contains **312,882 employee records** with information such as job title, base pay, overtime pay, other pay, benefits, total pay, total compensation, and year.

### Key Work Completed:
- Performed exploratory data analysis and examined the structure and characteristics of the dataset.
- Cleaned and converted salary-related features into appropriate numerical formats.
- Handled missing values and prepared the dataset for machine learning.
- Applied **One-Hot Encoding** to categorical JobTitle data.
- Built machine learning pipelines using Scikit-learn.
- Split the data into training and testing sets using an 80/20 split.
- Trained and evaluated multiple regression models:
  - Linear Regression
  - Gradient Boosting Regressor
  - Random Forest Regressor
- Evaluated the models using **R² Score and RMSE**.
- Compared actual vs. predicted salaries using visualization.
- Performed residual/error analysis to better understand model performance.

### Model Results:
- Linear Regression: **R² = 83.14%**
- Gradient Boosting: **R² = 95.74%**
- Random Forest: **R² = 96.53%**

The **Random Forest Regressor achieved the best performance**, making it the strongest model among the tested approaches for predicting employee total pay.

### Technologies:
Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Machine Learning | Data Analysis | Regression

This project demonstrates practical experience in **data preprocessing, exploratory analysis, feature encoding, machine learning model development, evaluation, and model comparison**.
