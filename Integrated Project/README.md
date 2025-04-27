Video Game Sales Forecasting - Integrated Project

A machine learning project to predict future global video game sales based on historical and product data.

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

This project aims to predict future video game sales to support strategic planning for a video game publishing company.
Using historical sales, critic/user ratings, platform, and genre data, machine learning models are trained to forecast sales figures.

The project follows a full data science pipeline, including:
	•	Data preprocessing
	•	Feature engineering
	•	Model selection
	•	Evaluation and tuning

Dataset

The dataset includes:
	•	Game title
	•	Platform
	•	Year of release
	•	Genre
	•	Publisher
	•	Critic score
	•	User score
	•	Historical global sales

(Data provided as part of the TripleTen curriculum.)

Project Objectives
	•	Prepare the data for machine learning models (handle missing values, encode categorical variables, etc.)
	•	Train multiple regression models
	•	Evaluate model performance with appropriate metrics (e.g., RMSE)
	•	Select the best-performing model for deployment
	•	Provide business recommendations based on predictive performance

Technologies Used
	•	Python
	•	Pandas
	•	Scikit-learn
	•	Matplotlib
	•	Seaborn
	•	Jupyter Notebook

How to Run
	1.	Clone the repository:

git clone https://github.com/ChavezData/Tripleten_projects.git

	2.	Navigate to the project directory:

cd Tripleten_projects/Integrated Project

	3.	Open the notebook:

You can open Project 5_Integrated Project(Video_Game_Sales_Forecasting).ipynb with Jupyter Notebook or Google Colab.

Install the required libraries:

pip install pandas scikit-learn matplotlib seaborn

	4.	Run the notebook cells sequentially to reproduce the results.

Modeling Approach
	•	Data Preprocessing:
	•	Handling missing values
	•	Encoding categorical features
	•	Feature scaling
	•	Model Training:
	•	Linear Regression
	•	Decision Tree Regressor
	•	Random Forest Regressor
	•	Evaluation:
	•	Models compared based on RMSE (Root Mean Squared Error)
	•	Cross-validation techniques applied to avoid overfitting

Key Findings
	•	Tree-based models (Random Forest) performed better than simple linear models.
	•	Proper handling of categorical variables and missing data was crucial for model performance.
	•	Sales predictions can guide resource allocation and marketing strategies for new game releases.

(For detailed metrics and plots, see the final sections of the notebook.)

Contributing

Contributions are welcome!
Please fork the repository and submit a pull request if you want to suggest improvements, tune the models further, or add alternative approaches.

License

This project is licensed under the MIT License.

Contact

Chavez Data
GitHub: @ChavezData
