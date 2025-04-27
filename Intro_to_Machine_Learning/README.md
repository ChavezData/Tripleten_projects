Customer Churn Prediction - Megaline Mobile Carrier Project

A machine learning project predicting customer churn to help a telecom company (Megaline) improve retention strategies.

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

In this project, I apply machine learning to predict which customers of the telecom company Megaline are likely to leave (“churn”).
By analyzing customer behavior data, the project helps the company identify at-risk customers and design targeted retention campaigns.

This project follows a full data science cycle, including preprocessing, model training, evaluation, and optimization.

Dataset

The dataset contains customer information, including:
	•	Number of calls
	•	Internet usage (MB)
	•	Message volume (SMS)
	•	Monthly charges
	•	Contract length

(Data provided as part of the TripleTen curriculum.)

Project Objectives
	•	Explore and prepare the customer behavior data
	•	Train various classification models to predict churn
	•	Compare model performances based on accuracy and business needs
	•	Select the best model for deployment
	•	Suggest strategic actions based on model insights

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

cd Tripleten_projects/Intro_to_Machine_Learning

	3.	Open the notebook:

You can open Project 6_Introduction_to_Machine_Learning(Mobile_Carrier_Megaline_Project).ipynb with Jupyter Notebook or Google Colab.
	4.	Install the required Python packages:

pip install pandas numpy scikit-learn matplotlib seaborn

	5.	Run the notebook cells sequentially.

Modeling Approach
	•	Data Preprocessing:
	•	Handling missing values
	•	Feature scaling and encoding (if necessary)
	•	Model Training:
	•	Decision Tree Classifier
	•	Random Forest Classifier
	•	Logistic Regression
	•	Evaluation:
	•	Models assessed based on accuracy, precision, recall, and ROC-AUC score
	•	Cross-validation used for robust evaluation

Key Findings
	•	The Random Forest Classifier achieved the best balance between precision and recall.
	•	Key predictors of churn included internet usage and monthly charges.
	•	Predicting churn enables the company to proactively reach out to customers and reduce attrition rates.

(Full evaluation metrics, confusion matrices, and business recommendations are provided inside the notebook.)

Contributing

Contributions are welcome!
If you’d like to improve model performance (e.g., using ensemble methods or hyperparameter tuning) or add new features, feel free to fork the repo and submit a pull request.

License

This project is licensed under the MIT License.

Contact

Chavez Data
GitHub: @ChavezData
