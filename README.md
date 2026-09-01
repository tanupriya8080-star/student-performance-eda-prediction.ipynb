 Student Performance in Exams – Writing Score Prediction

A Machine Learning project that analyzes student performance and predicts **Writing Score** using Exploratory Data Analysis (EDA) and multiple regression algorithms.



 About The Project

Student academic performance can be influenced by various demographic, educational, and academic factors.

This project analyzes a dataset containing **1,000 student records** and explores the relationships between different student characteristics and their exam scores.

The main goal of this project is to **predict a student's Writing Score** using relevant features such as:

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch
* Test Preparation Course
* Math Score
* Reading Score

Several Machine Learning regression models are implemented and compared to identify the model with the best predictive performance.


 Objectives

* Perform Exploratory Data Analysis on student performance data.
* Understand the distribution of student demographic and educational characteristics.
* Analyze relationships between Math, Reading, and Writing scores.
* Identify important factors related to Writing Score.
* Preprocess categorical and numerical data.
* Build regression models for Writing Score prediction.
* Evaluate and compare different Machine Learning models.
* Select the best-performing model based on evaluation metrics.


 Dataset

The dataset contains **1,000 student records** with the following features:

| Column                      | Description                    |
| --------------------------- | ------------------------------ |
| Gender                      | Gender of the student          |
| Race/Ethnicity              | Race/Ethnicity group           |
| Parental Level of Education | Education level of parent(s)   |
| Lunch                       | Type of lunch received         |
| Test Preparation Course     | Test preparation course status |
| Math Score                  | Mathematics examination score  |
| Reading Score               | Reading examination score      |
| Writing Score               | Writing examination score      |

 Target Variable

**Writing Score**

 Exploratory Data Analysis

The project includes different EDA techniques to understand the dataset and discover meaningful patterns.

Analysis Performed

* Dataset structure and information
* Missing value analysis
* Categorical variable analysis
* Student demographic analysis
* Score distributions
* Gender-wise analysis
* Race/Ethnicity analysis
* Lunch analysis
* Test Preparation Course analysis
* Relationship between Math and Writing Scores
* Relationship between Reading and Writing Scores
* Correlation analysis

 Data Preprocessing

The following preprocessing steps are performed:

1. Load the dataset.
2. Understand the dataset structure.
3. Check for missing values.
4. Separate input features and target variable.
5. Encode categorical variables.
6. Prepare the data for Machine Learning.
7. Split the data into training and testing sets.

 🤖 Machine Learning Models

The following regression algorithms are used:

 1. Linear Regression

Used as a baseline model to establish the relationship between the input features and Writing Score.

 2. Decision Tree Regressor

A tree-based regression algorithm capable of capturing non-linear relationships in the data.

 3. Random Forest Regressor

An ensemble learning algorithm that combines multiple decision trees to improve prediction performance.

4. Gradient Boosting Regressor

An ensemble technique that builds models sequentially to reduce prediction errors.

 Model Evaluation

The models are evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

Model Performance

| Model                 |   R² Score |
| --------------------- | ---------: |
| **Linear Regression** | **0.9436** |
| Random Forest         |     0.9330 |
| Gradient Boosting     |     0.9282 |
| Decision Tree         |     0.8817 |

 Linear Regression Metrics

| Metric   |   Score |
| -------- | ------: |
| MAE      |  2.9488 |
| MSE      | 13.5701 |
| RMSE     |  3.6838 |
| R² Score |  0.9436 |

 Results

Among the tested models, **Linear Regression achieved the highest R² score of 0.9436**.

This indicates that Linear Regression performed better than the other evaluated models for predicting Writing Score on the test data.

The project also demonstrates a strong relationship between students' **Math, Reading, and Writing Scores**.

 Project Workflow

text
Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Feature Encoding
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Best Model Selection

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Jupyter Notebook
* Git
* GitHub

 Project Structure

text
Student-Performance-Writing-Score/
│
├── Student_Performance_EDA_Prediction.ipynb
├── README.md
├── dataset/
│   └── StudentsPerformance.csv
│
└── images/
    └── visualizations/

> Update the filenames/folders if your GitHub repository uses different names.

 How to Run
 Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the Project

Open the Jupyter Notebook:

```text
Student_Performance_EDA_Prediction.ipynb
```

You can run the notebook using **Jupyter Notebook** or **Google Colab**.

Run the cells sequentially to perform data analysis, visualization, model training, and evaluation.

---
 Future Scope

This project can be further improved by:

* Applying hyperparameter tuning.
* Using cross-validation techniques.
* Testing additional Machine Learning algorithms.
* Adding more student-related features.
* Using larger educational datasets.
* Developing an interactive prediction application.
* Deploying the trained model as a web application.
* Exploring advanced Machine Learning and Deep Learning techniques.

---
 References

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Student Performance Dataset


Author

**Tanu Priya**

B.Tech – Computer Science


 Conclusion

This project demonstrates how **Exploratory Data Analysis and Machine Learning** can be used to analyze student academic performance and predict Writing Score.

Multiple regression models were implemented and compared, with **Linear Regression achieving the best R² score of 0.9436** among the evaluated models.
