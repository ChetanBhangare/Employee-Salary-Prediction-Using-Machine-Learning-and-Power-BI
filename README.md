Employee Salary Prediction
Introduction
This project aims to predict employee salaries based on a variety of factors, including demographics, job roles, education, and performance metrics. By combining machine learning techniques in Python and data visualizations in Power BI, the project provides actionable insights to optimize compensation strategies and improve HR decision-making.

Features
Machine Learning Models:

Linear Regression
Logistic Regression
K-Nearest Neighbors (KNN)
Principal Component Analysis (PCA)
Natural Language Processing (NLP) techniques (TF-IDF, Count Vectorization)
Data Visualizations:

Power BI dashboard featuring insights such as workforce distribution, department-level salary trends, and demographic breakdowns.
Feature Engineering:

Interaction terms, polynomial features, and log transformations to capture non-linear relationships and improve model accuracy.
Clustering Analysis:

K-Means clustering to identify patterns in employee data, such as salary groups and performance clusters.
Project Highlights
Achieved 98% accuracy in salary prediction using Linear Regression with advanced feature engineering.
Developed a Power BI dashboard for interactive insights into employee demographics, experience, and salary trends.
Applied clustering to segment employees into salary ranges and performance groups.
Addressed data integrity issues through deduplication and label standardization, ensuring high-quality analysis.
Dataset Overview
The dataset consists of 10,000 rows with the following key attributes:

Demographics: Age, Gender, City, Country, Marital Status.
Job Information: Department, Position, Experience, Performance Score.
Compensation: Salary (Target variable for prediction).
Education: Education Level (High School, Bachelor's, PhD).
Folder Structure
Python/: Contains Python scripts for data preprocessing, feature engineering, and machine learning models.
PowerBI/: Includes the Power BI dashboard file (Employee_Salary_Dashboard.pbix).
Dataset/: Sample dataset used for training and analysis.
README.md: Overview and documentation of the project.
Installation and Setup
Prerequisites
Python 3.x
Power BI Desktop
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, nltk
Steps
Clone this repository:
bash
Copy
Edit
git clone https://github.com/your-username/Employee-Salary-Prediction.git  
cd Employee-Salary-Prediction  
Install the required Python libraries:
bash
Copy
Edit
pip install -r requirements.txt  
Open and explore the Power BI dashboard using Power BI Desktop.
How to Use
Run the Python scripts for:
Data preprocessing (data_cleaning.py)
Model training and evaluation (salary_prediction.py)
Visualize the results using the Power BI dashboard for interactive insights.
Key Insights
Machine Learning Results: Linear Regression outperformed other models with an R² score of 0.98, making it the best model for predicting salaries.
Visualization Insights: The Power BI dashboard provides a holistic view of salary distribution, department-level analysis, and demographic breakdowns.
Future Enhancements
Add employee attrition data to analyze turnover patterns.
Incorporate additional features like job satisfaction and psychological metrics.
Refine models with hyperparameter tuning to further improve accuracy.
Contributors
Chetan Bhangare
Feel free to explore and contribute to this project!
