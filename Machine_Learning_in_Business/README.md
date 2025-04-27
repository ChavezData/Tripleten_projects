Oil Well Profit Prediction - OilyGiant Mining Company

A machine learning project predicting the most profitable oil wells to optimize resource allocation for a mining company.

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

In this project, I build a predictive model to help OilyGiant, a mining company, decide where to drill for oil.
The project analyzes geological data and predicts oil production volumes to identify the most profitable regions for new wells, supporting better business decisions with machine learning.

The focus is not only on technical modeling, but also on financial analysis and risk assessment.

Dataset

The data includes information from three different oil regions:
	•	Features: Geological parameters for each potential well
	•	Target: Volume of oil production (in barrels)

(Data provided as part of the TripleTen curriculum.)

Project Objectives
	•	Train a model to predict oil production from geological data
	•	Identify the top 200 most promising wells in each region
	•	Calculate potential profits based on production forecasts
	•	Use statistical methods (bootstrapping) to estimate risks
	•	Recommend the most profitable and least risky region to invest in

Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	Scikit-learn
	•	Matplotlib
	•	Seaborn
	•	SciPy
	•	Jupyter Notebook

How to Run
	1.	Clone the repository:

git clone https://github.com/ChavezData/Tripleten_projects.git

	2.	Navigate to the project directory:

cd Tripleten_projects/Machine_Learning_in_Business

	3.	Open the notebook:

You can open Project 9_Machine_Learning_in_Business(OilyGiant_Mining_Company).ipynb with Jupyter Notebook or Google Colab.
	4.	Install the required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn scipy

	5.	Run the notebook step-by-step to reproduce the analysis and results.

Modeling Approach
	•	Data Exploration:
	•	Analyze distributions and correlations between features and target variable.
	•	Model Training:
	•	Linear Regression used to predict production volume.
	•	Region Analysis:
	•	Select top 200 wells with the highest predictions per region.
	•	Profit Calculation:
	•	Calculate revenue based on predicted production and investment cost.
	•	Risk Assessment:
	•	Apply bootstrapping to evaluate profit distribution and risk probabilities for each region.

Key Findings
	•	Built reliable regression models for production volume prediction.
	•	Identified the region offering the highest expected profit with acceptable risk.
	•	Provided data-driven recommendations for strategic investment decisions.
	•	Demonstrated the value of combining machine learning and business metrics in operational planning.

(All detailed calculations, profit estimates, and final recommendations are presented inside the notebook.)

Contributing

Contributions are welcome!
If you would like to propose new modeling techniques (e.g., using more advanced regressors) or better risk estimation methods, feel free to fork the repo and submit a pull request.

License

This project is licensed under the MIT License.

Contact

Chavez Data
GitHub: @ChavezData
