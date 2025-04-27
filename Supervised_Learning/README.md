Customer Churn Prediction - Beta Bank

A supervised machine learning project to predict customer churn for Beta Bank and help retain valuable clients.

Table of Contents
	•	About
	•	Dataset
	•	Project Objectives
	•	Technologies Used
	•	How to Run
	•	Modeling Approach
	•	Key Findings
	•	Contributing
	•	License
	•	Contact

About

In this project, I develop a supervised machine learning model to predict whether customers of Beta Bank are likely to leave (churn).
Early identification of potential churners allows the business to take proactive steps to retain valuable clients and improve customer satisfaction.

The project focuses on classification techniques, feature engineering, and model evaluation to achieve a high level of prediction accuracy.

Dataset

The dataset includes information such as:
	•	Customer demographics (age, gender)
	•	Bank account details (balance, number of products)
	•	Credit scores
	•	Tenure at the bank
	•	Churn status (target variable)

(Data provided as part of the TripleTen curriculum.)

Project Objectives
	•	Understand the factors leading to customer churn
	•	Build and train a predictive classification model
	•	Evaluate model performance using appropriate metrics
	•	Deliver actionable business insights to improve customer retention strategies

Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	Scikit-learn
	•	Matplotlib
	•	Seaborn
	•	Jupyter Notebook

How to Run
	1.	Clone the repository:

git clone https://github.com/ChavezData/Tripleten_projects.git

	2.	Navigate to the project directory:

cd Tripleten_projects/Supervised_Learning

	3.	Open the notebook:

You can open Project 8_Supervised_Learning(Beta_Bank_Customers).ipynb with Jupyter Notebook or Google Colab.
	4.	Install the required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn

	5.	Run the notebook step-by-step to reproduce the analysis and results.

Modeling Approach
	•	Data Exploration and Preprocessing:
	•	Handle missing values and outliers
	•	Encode categorical variables
	•	Feature scaling for model optimization
	•	Model Training:
	•	Trained several classification algorithms:
	•	Logistic Regression
	•	Decision Trees
	•	Random Forests
	•	Gradient Boosting
	•	Model Evaluation:
	•	Evaluated using accuracy, precision, recall, F1-score, and ROC-AUC
	•	Selected the best-performing model based on business objectives (e.g., prioritizing recall to catch more churners)

Key Findings
	•	Identified key factors contributing to customer churn, including account balance, credit score, and tenure.
	•	Achieved high ROC-AUC scores with the selected model, making it effective for real-world deployment.
	•	Provided business strategies such as targeted loyalty programs for customers at high risk of leaving.

(Detailed model results, comparisons, and business recommendations are provided inside the notebook.)

Contributing

Contributions are welcome!
If you want to explore feature engineering improvements, advanced models like XGBoost, or model explainability (e.g., SHAP values), feel free to fork the repo and submit a pull request.

License

This project is licensed under the MIT License.

Contact

Chavez Data
GitHub: @ChavezData
