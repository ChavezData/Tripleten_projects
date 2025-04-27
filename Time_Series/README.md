Taxi Demand Forecasting - Sweet Lift Taxi Company

A time series forecasting project to predict taxi demand and optimize operations for a ride-hailing service.

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

In this project, I develop a time series model to predict the number of taxi rides per hour for the Sweet Lift Taxi Company.
The goal is to forecast demand accurately to help the company allocate resources more efficiently and minimize idle time or service shortages.

The project uses time series analysis techniques, feature engineering, and model optimization to deliver actionable insights.

Dataset

The dataset contains:
	•	Timestamps of taxi orders
	•	Number of completed rides per hour

(Data provided as part of the TripleTen curriculum.)

Project Objectives
	•	Explore and visualize taxi ride demand over time
	•	Engineer relevant features for time series forecasting
	•	Build and train predictive models
	•	Evaluate model performance using time series-specific metrics
	•	Provide business recommendations based on forecasting results

Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	Scikit-learn
	•	Matplotlib
	•	Seaborn
	•	Jupyter Notebook
	•	Statsmodels

How to Run
	1.	Clone the repository:

git clone https://github.com/ChavezData/Tripleten_projects.git

	2.	Navigate to the project directory:

cd Tripleten_projects/Time_Series

	3.	Open the notebook:

You can open Project 13_Time_Series(Sweet_Lift_Taxi_Company).ipynb with Jupyter Notebook or Google Colab.
	4.	Install the required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn statsmodels

	5.	Run the notebook step-by-step to reproduce the analysis.

Modeling Approach
	•	Data Exploration:
	•	Visualization of demand patterns by hour, day, and week
	•	Analysis of trends, seasonality, and noise
	•	Feature Engineering:
	•	Lag features (previous hours)
	•	Rolling averages and statistical features
	•	Extraction of time-based features (hour, weekday)
	•	Model Training:
	•	Linear Regression
	•	Decision Tree Regressor
	•	Evaluation:
	•	Root Mean Squared Error (RMSE) used for model evaluation
	•	Comparison of different model performances

Key Findings
	•	Demand exhibits clear hourly and weekly seasonality.
	•	Lag features and rolling averages significantly improved model performance.
	•	The final model achieved strong forecasting accuracy and can be used for workforce planning, dynamic pricing, and customer service improvements.

(Detailed visualizations, error metrics, and business insights are included in the notebook.)

Contributing

Contributions are welcome!
If you want to explore more advanced forecasting methods (e.g., ARIMA, Prophet, or LSTM networks), feel free to fork the repo and submit a pull request.

License

This project is licensed under the MIT License.

Contact

Chavez Data
GitHub: @ChavezData
