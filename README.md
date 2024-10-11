# Titanic Survival Prediction Project 🛳️

## Overview
This project focuses on predicting the survival of passengers aboard the Titanic using machine learning techniques. The dataset provides details of the passengers, such as their age, gender, class, and other characteristics. By analyzing these features, we aim to build a model that can accurately predict whether a passenger survived or not.

The project demonstrates the following key data science skills:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering
- Model training and evaluation using machine learning algorithms

## Dataset 📊
The dataset used for this project is the famous **Titanic dataset** from [Kaggle](https://www.kaggle.com/c/titanic/data). It contains 891 rows and 12 features, including:
- **PassengerId**: Unique identifier for each passenger.
- **Pclass**: Ticket class (1st, 2nd, or 3rd).
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings or spouses aboard the Titanic.
- **Parch**: Number of parents or children aboard the Titanic.
- **Fare**: Ticket fare.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Insights 🔍
Through **Exploratory Data Analysis (EDA)**, several key insights were uncovered:
1. **Gender**: Females had a significantly higher survival rate than males, indicating that gender played a crucial role in survival chances.
2. **Class**: First-class passengers had a higher survival rate compared to second and third class, showing that wealth and class status had an impact on survival.
3. **Age**: Younger passengers, especially children, had higher survival rates, likely due to the "women and children first" rescue rule.
4. **Family Size**: Passengers with smaller families tended to have better chances of survival.

## Models and Techniques 🧠
The project uses the following machine learning models and techniques:
- **RandomForestClassifier**: A robust and ensemble-based machine learning model to predict survival.
- **Logistic Regression**: A basic but interpretable model to compare performance.
- **Feature Engineering**: Features like FamilySize were created to capture additional patterns in the data.
- **Model Evaluation**: Accuracy, precision, recall, and F1-score were used to evaluate model performance.

## Getting Started 🚀
To run this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/titanic-survival-prediction.git
    cd titanic-survival-prediction
    ```

2. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook (or Colab) for data analysis and model training:
    - You can open the `Titanic_Survival_Prediction.ipynb` file in Jupyter or Colab and run the code cells.

## Results 🏆
After training the **RandomForestClassifier**, the model achieved an accuracy of **~80%** on the test set. This suggests that the model can effectively predict survival based on passenger data.

## Future Work 🔮
Possible improvements to the model could include:
- **Hyperparameter tuning** of the Random Forest model to further boost performance.
- Trying other machine learning algorithms like **XGBoost** or **SVM**.
- Addressing missing data through more advanced imputation techniques.



