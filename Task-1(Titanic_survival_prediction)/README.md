# Titanic Survival Prediction 🚢
Project Overview

This project aims to predict whether a passenger survived the Titanic disaster or not using machine learning techniques. The dataset contains various features like age, gender, ticket class, and other relevant information, which can be used to train a predictive model. This is a beginner-friendly project in data science and machine learning.


Author: Ramanuj Kumar

Batch: Sep-Oct

Domain: Data Science

Dataset:

The dataset used for this project contains information on 418 passengers. It includes the following features:

    Pclass: Passenger class (1st, 2nd, 3rd)
    Age: Age of the passenger
    Sex: Gender (male, female)
    SibSp: Number of siblings or spouses aboard the Titanic
    Parch: Number of parents or children aboard the Titanic
    Fare: Ticket fare paid by the passenger
    Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Steps in the Project:

    Data Loading: The Titanic dataset is loaded and initial observations are made.
    Data Cleaning: Missing values in columns such as Age, Fare, and Embarked were handled. The Cabin column, which had a large number of missing values, was dropped.
    Exploratory Data Analysis (EDA): Visualizations and statistical summaries were generated to understand the data better.
    Feature Engineering: Relevant features were selected for model training.
    Model Building: Machine learning algorithms were applied to predict passenger survival.
    Evaluation: The model performance was evaluated based on various metrics.

Tools and Libraries Used:

    Pandas for data manipulation
    NumPy for numerical operations
    Matplotlib and Seaborn for data visualization
    Scikit-learn for machine learning model building

Key Insights:

    Certain features like gender (Sex), passenger class (Pclass), and ticket fare (Fare) significantly influence the survival prediction.
    Data preprocessing and handling missing values are crucial steps to improve the model's accuracy.

Conclusion:

The project successfully predicts the likelihood of survival for Titanic passengers based on the provided dataset. It serves as a foundational project for understanding data preprocessing, exploratory data analysis, and model building in data science.
How to Use:

    Clone this repository:
    git clone (https://github.com/Ramanuj1110/CODESOFT/blob/main/Titanic_prediction_model.ipynb)
    Install the required libraries:
    pip install -r requirements.txt
    Run the Jupyter notebook to explore the data and the model-building process.

License

This project is licensed under the MIT License.
