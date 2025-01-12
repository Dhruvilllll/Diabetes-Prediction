# Diabetes Prediction

This project aims to build a machine learning model to predict the onset of diabetes in patients based on various health indicators.

**1. Data:**

* Used the Pima Indians Diabetes Dataset, a well-known dataset for diabetes prediction.
* The dataset contains features such as:
    * Pregnancies
    * Glucose
    * BloodPressure
    * SkinThickness
    * Insulin
    * BMI
    * DiabetesPedigreeFunction
    * Age
* Target variable: Outcome (0: No diabetes, 1: Diabetes)

**2. Data Preprocessing:**

* Handled missing values (e.g., replacing with mean, median, or using imputation techniques).
* Performed exploratory data analysis (EDA) to understand the distribution of features and their relationships with the target variable.
* Split the dataset into training and testing sets using train_test_split.

**3. Model Building and Evaluation:**

* Trained various classification models, including:
    * Support Vector Machine (SVM)
* Evaluated model performance using metrics such as accuracy and precision.
* Performed hyperparameter tuning using techniques like Randomized Search to optimize model performance.

**4. Technologies Used:**

* Python
* Pandas
* NumPy
* Scikit-learn
* SVM (Support Vector Machine)
