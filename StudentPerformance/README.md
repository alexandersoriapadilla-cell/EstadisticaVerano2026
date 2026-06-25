# Student Performance Dataset

## Description

The Student Performance Dataset is designed to examine the factors that influence students' academic performance. The dataset contains **10,000 student records**, where each record includes information about several predictor variables and a target variable representing overall student performance.

The dataset can be used for exploratory data analysis, statistical studies, and machine learning applications to better understand how different factors contribute to academic success.


---

## Variables

### Predictor Variables

| Variable | Type | Description |
|-----------|------|-------------|
| Hours Studied | Numerical | Total number of hours spent studying by the student. |
| Previous Scores | Numerical | Scores obtained by the student in previous tests. |
| Extracurricular Activities | Categorical (Yes/No) | Indicates whether the student participates in extracurricular activities. |
| Sleep Hours | Numerical | Average number of hours the student sleeps per day. |
| Sample Question Papers Practiced | Numerical | Number of sample question papers practiced by the student. |

### Target Variable

| Variable | Type | Description |
|-----------|------|-------------|
| Performance Index | Numerical | Overall academic performance score ranging from **10 to 100**, where higher values indicate better performance. The score has been rounded to the nearest integer. |

---

## Objective

The primary objective of this dataset is to analyze the relationship between various academic and lifestyle factors and student performance. Researchers and data analysts can use this dataset to:

- Identify the most influential factors affecting academic performance.
- Explore correlations between study habits and performance outcomes.
- Build predictive models for estimating student performance.
- Evaluate the impact of extracurricular activities and sleep patterns on academic achievement.

---

## Potential Research Questions

1. How does the number of hours studied affect academic performance?
2. Are previous academic scores strong predictors of future performance?
3. Does participation in extracurricular activities influence academic outcomes?
4. What is the relationship between sleep duration and performance?
5. Does practicing more sample question papers lead to higher performance scores?

---

## Machine Learning Perspective

This dataset represents a **supervised learning regression problem**, where:

- **Input Features (X):**
  - Hours Studied
  - Previous Scores
  - Extracurricular Activities
  - Sleep Hours
  - Sample Question Papers Practiced

- **Target Variable (y):**
  - Performance Index

Possible regression algorithms include:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression
- XGBoost
- LightGBM

---

## Suggested Exploratory Data Analysis (EDA)

The following analyses can be performed:

### Univariate Analysis
- Distribution of Performance Index
- Distribution of study hours
- Distribution of sleep hours

### Bivariate Analysis
- Hours Studied vs Performance Index
- Previous Scores vs Performance Index
- Sleep Hours vs Performance Index

### Multivariate Analysis
- Correlation matrix
- Feature importance analysis
- Pairwise relationships among variables

---

## Suggested Visualizations

- Histogram of Performance Index
- Correlation Heatmap
- Scatter Plots
- Box Plots
- Pair Plots
- Feature Importance Charts

---

## Expected Relationships

Based on the dataset design, the following trends may be observed:

- More study hours are associated with higher performance.
- Higher previous scores tend to predict better future performance.
- Practicing more sample papers may improve performance.
- Adequate sleep may positively influence academic results.
- Participation in extracurricular activities may have a positive or neutral effect on performance.

---

## License

This dataset is synthetic and intended for educational and illustrative purposes. The relationships represented in the data may not reflect real-world scenarios.

**License:** Anyone is free to use, share, and distribute the dataset.

La base de datos esta [aquí](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression)
