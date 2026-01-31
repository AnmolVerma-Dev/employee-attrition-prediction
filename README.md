**Project Overview**

* Employee attrition is a common problem in organizations and directly affects productivity and cost.
  This project focuses on analyzing employee data and building a machine learning model to predict whether an employee is likely to leave the company.

* The project is built to demonstrate practical data analysis and machine learning workflow, not just model accuracy.

**Objective**

* Understand factors that contribute to employee attrition

* Perform exploratory data analysis on HR data

* Preprocess and prepare data for modeling

* Build and evaluate a classification model to predict attrition

**Dataset**

* Source: HR Employee Attrition dataset

* Format: CSV

* Target Variable: Attrition (Yes / No)

* The dataset contains employee information such as:

  >Age, Gender, Department, Job Role, Job Satisfaction, Monthly Income, Overtime, Years at Company, Performance Rating

**Tools & Libraries Used**

* Python

* Pandas & NumPy – data handling

* Matplotlib & Seaborn – visualization

* Scikit-learn – preprocessing, modeling, evaluation

* Imbalanced-learn – handling class imbalance

* Jupyter Notebook

**Project Workflow**

1. Data Loading & Inspection

   * Loaded the dataset using Pandas

   * Checked data types, missing values, and duplicates

   * Removed duplicate records
2. Exploratory Data Analysis (EDA)

   * Analyzed distribution of attrition

   * Visualized relationships between attrition and features like:

       * Job Role

       * Overtime

       * Monthly Income

       * Job Satisfaction
3. Data Preprocessing

   * Encoded categorical variables using Label Encoding

   * Split data into features and target

   * Handled class imbalance using Random OverSampling

   * Scaled features where required
4. Model Building

   * Trained a Logistic Regression model

   * Used train-test split for evaluation
5. Model Evaluation

   * Accuracy score

   * Confusion Matrix

   * Classification performance analysis

**How to run the project**
  * Clone the respository
     * https://github.com/AnmolVerma-Dev/employee-attrition-prediction.git
  * Install required libraries
     * pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
  * Open the Jupyter Notebook and run cells step by step
  
