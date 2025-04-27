Gold Ore Recovery Prediction - Integrated Project 2

A machine learning project predicting the recovery rate of gold from ore, optimizing extraction processes in the mining industry.

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

In this project, I work on predicting the final recovery rates of gold extracted from ore during an industrial process.
The goal is to build a reliable machine learning model that can help optimize processing parameters, improve efficiency, and reduce production losses.

The work covers a complete data science workflow: data cleaning, feature engineering, model training, validation, and business-focused evaluation.

Dataset

The provided dataset contains:
	•	Physical and chemical parameters at various processing stages (rougher, final)
	•	Gold, silver, and concentrate measurements
	•	Recovery targets for training the models

(Data provided as part of the TripleTen curriculum.)

Project Objectives
	•	Analyze and clean the industrial ore processing data
	•	Engineer meaningful features for modeling
	•	Train multiple machine learning regression models
	•	Evaluate models using business-relevant metrics
	•	Recommend the best-performing model for practical deployment

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

cd Tripleten_projects/Integrated_Project_2

	3.	Open the notebook:

You can open Project 10_Integrated_Project_2(Gpld_Ore_Project).ipynb with Jupyter Notebook or Google Colab.
	4.	Install the necessary Python packages:

pip install pandas numpy scikit-learn matplotlib seaborn

	5.	Run the notebook cells sequentially to reproduce the analysis.

Modeling Approach
	•	Data Preprocessing:
	•	Handling missing values
	•	Feature selection and reduction
	•	Normalization of numeric features
	•	Model Training:
	•	Linear Regression
	•	Decision Tree Regressor
	•	Random Forest Regressor
	•	Evaluation:
	•	Models assessed primarily by sMAPE (Symmetric Mean Absolute Percentage Error), an industry-relevant metric
	•	Special focus on model stability across training, validation, and test sets

Key Findings
	•	Random Forest Regressor outperformed other models in terms of predictive accuracy and stability.
	•	Proper data cleaning (especially dealing with missing values at different process stages) was critical to model success.
	•	Predicting recovery rates can substantially improve production planning and reduce financial losses for mining companies.

(Complete modeling results, metric values, and insights are detailed inside the notebook.)

Contributing

Contributions are welcome!
Feel free to fork the repo, propose improvements (e.g., advanced models like Gradient Boosting), or suggest different feature engineering techniques.

License

This project is licensed under the MIT License.

Contact

Chavez Data
GitHub: @ChavezData
