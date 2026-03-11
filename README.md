# Campus Recruitment Prediction Model

## Context

Campus placements play a crucial role in shaping the careers of students. However, many students prepare for placements without a clear understanding of the factors that significantly influence hiring outcomes. Questions such as whether academic performance, specialization, work experience, or employability skills matter the most often remain unclear.

At the same time, educational institutions collect large volumes of placement data each year, but this data is rarely analyzed systematically to generate actionable insights. As a result, both students and placement cells rely heavily on assumptions rather than data-driven decision making.

To address this problem, I developed the **Campus Recruitment Prediction Model**, a machine learning project designed to analyze historical student placement data and predict whether a student is likely to be placed based on various academic and professional attributes.

The dataset used in this project includes features such as:

- Gender
- Secondary and higher secondary education performance
- Undergraduate degree and specialization
- Work experience
- Employability test scores
- Placement status

The goal of this project is to use **machine learning techniques to uncover patterns in placement data** and build a predictive model that can estimate a student's placement likelihood.

Beyond prediction, the project also aims to demonstrate how data-driven insights can help:

- Students better understand their placement readiness
- Training and Placement Cells identify areas where students require additional support
- Institutions design targeted skill development programs

This project follows a complete **machine learning workflow**, including data preprocessing, feature engineering, model training, evaluation, and performance comparison across multiple algorithms.

Ultimately, the long-term vision is to evolve this model into a **decision-support tool or analytics dashboard** that helps institutions improve placement outcomes and enables students to prepare more strategically.
## Project Workflow

1. Data Exploration and Analysis  
2. Data Preprocessing and Cleaning  
3. Handling Class Imbalance using SMOTE  
4. Model Training (Logistic Regression, Random Forest, XGBoost)  
5. Model Evaluation and Performance Comparison  
6. Feature Importance Analysis
7. ## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Jupyter Notebook
  ## Model Performance

Final model: **XGBoost**

- Accuracy: 86%
- Precision: 87%
- Recall: 93%
  ## Future Improvements

- Include additional features such as internships and extracurricular activities
- Build an interactive web dashboard for students
- Deploy the model as a web application
- Retrain the model with updated placement datasets
