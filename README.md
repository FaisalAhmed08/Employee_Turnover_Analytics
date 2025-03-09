**Employee Turnover Prediction**
Project Overview:
Employee turnover is a critical challenge for businesses. This machine learning project aims to predict whether an employee is likely to leave the company based on various factors such as satisfaction level, last evaluation score, and salary category. The objective is to provide insights that help companies improve employee retention strategies.

**File Structure**
Employee_Turnover_Analytics_Project  
 ├── README.md  (Project description)  
 ├── Employee_Turnover_Dataset.csv  (Dataset file)  
 ├── Employee_Turnover_Project.ipynb  (Jupyter Notebook containing analysis and model training)  


**Installation and Usage**
To run this project on your local machine, follow these steps:

1.Clone this Repository:
  git clone https://github.com/your-username/Employee_Turnover_Analytics_Project.git

2.Navigate to Project Folder:
  cd Employee_Turnover_Analytics_Project

3.Install Dependancies
  pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn

4.Open Jupyter Notebook
  jupyter notebook


**Dataset**
File Name: Employee_Turnover_Dataset.csv
Features:
*Satisfaction Level
*Last Evaluation Score
*Average Monthly Hours
*Time Spent in Company
*Number of Projects
*Department
*Salary Category

Target Variable:
*Left (1 = Employee Left, 0 = Employee Stayed)

**Machine Learning Workflow**
Data Cleaning & Preprocessing: Handling missing values, encoding categorical variables, and normalizing numerical features.

Exploratory Data Analysis (EDA): Identifying key factors influencing employee turnover through data visualization.

Handling Class Imbalance: Using SMOTE (Synthetic Minority Over-sampling Technique) .

Feature Engineering: Selecting the most important features.

Model Training & Evaluation: Training models such as Logistic Regression, Random Forest, and Gradient Boosting, and evaluating performance using accuracy, precision, recall, F1-score, and ROC-AUC.

Final Model Selection: Choosing the best-performing model for predictive insights.

**Contributing**
Contributions are welcome. If you have suggestions or improvements, feel free to submit an issue or a pull request.

**Contact**
For any inquiries or feedback, please reach out via GitHub issues.
