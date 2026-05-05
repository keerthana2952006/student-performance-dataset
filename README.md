📘 Student Performance Dataset 

This dataset contains student academic and behavioral data, converted into numeric format for machine learning tasks. It is designed to classify students into Best (1) or Worst (0) based on multiple factors.

📊 Dataset Overview

Rows: 30 students
Columns: 15 features
Target Variable: Performance
Each row represents one student, and each column represents a feature used for prediction.

🧾 Features Description
| Column Name    | Description                     |
| -------------- | ------------------------------- |
| ID             | Unique student ID               |
| Name           | Student name                    |   
| Age            | Age of student                  |
| Gender         | Encoded gender                  |
| Class          | Student grade                   |
| Math           | Marks in Mathematics            |
| Science        | Marks in Science                |
| English        | Marks in English                |
| Attendance     | Attendance percentage           |
| Sports         | Sports participation            |
| Cultural       | Cultural activity participation |
| Behavior       | Student behavior level          |
| Study Hours    | Daily study hours               |
| Internet Usage | Internet usage level            |
| Performance    | Target (Best/Worst)             |

🔢 Data Encoding

Categorical values are converted into numeric values:
Gender: Male = 0, Female = 1
Sports / Cultural: Yes = 1, No = 0
Behavior: Good = 3, Average = 2, Poor = 1
Internet Usage: High = 0, Medium = 1, Low = 2
Performance: Best = 1, Worst = 0

🎯 Performance Criteria (Important)
The Performance (target variable) is determined based on the following key factors:
Math marks
Science marks
English marks
Attendance percentage
Behavior
Study hours
These features are combined to evaluate overall student performance and classify them into:
Best (1) → High-performing students
Worst (0) → Low-performing students

🎯 Objective

The goal of this dataset is to:
Analyze student performance
Apply data preprocessing techniques
Train machine learning models for classification
Understand how academic and behavioral factors influence performance

⚙️ Use Cases

Data analysis using Pandas
Data visualization using Matplotlib / Seaborn
Classification models (Logistic Regression, Decision Tree)
Academic performance prediction

⚠️ Note

This dataset is manually created for learning purposes
It follows a rule-based approach for generating the target variable
Suitable for beginners in ML and data science
