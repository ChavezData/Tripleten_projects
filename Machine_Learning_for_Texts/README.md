Movie Review Sentiment Analysis - The Film Junky Union

A machine learning project analyzing movie reviews to predict audience sentiment using natural language processing (NLP) techniques.

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

In this project, I build a text classification model to help The Film Junky Union automatically assess movie reviews.
The main goal is to predict whether a given review is positive or negative based on its content, enabling faster insights into public opinion without manual review.

This project combines natural language processing (NLP) techniques with machine learning models to perform text classification.

Dataset

The dataset includes:
	•	User-submitted movie reviews (free text)
	•	Binary sentiment labels (positive or negative)

(Data provided as part of the TripleTen curriculum.)

Project Objectives
	•	Preprocess text data for machine learning
	•	Explore different vectorization methods
	•	Train and compare classification models
	•	Optimize model performance for real-world deployment
	•	Deliver business insights based on model results

Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	Scikit-learn
	•	NLTK (Natural Language Toolkit)
	•	Jupyter Notebook

How to Run
	1.	Clone the repository:

git clone https://github.com/ChavezData/Tripleten_projects.git

	2.	Navigate to the project directory:

cd Tripleten_projects/Machine_Learning_for_Texts

	3.	Open the notebook:

You can open Project 14_Machine_Learning_for_Texts(The_Film_Junky_Union).ipynb with Jupyter Notebook or Google Colab.
	4.	Install the required libraries:

pip install pandas numpy scikit-learn nltk

	5.	Run the notebook cells step-by-step to reproduce the analysis.

Modeling Approach
	•	Text Preprocessing:
	•	Lowercasing, punctuation removal
	•	Tokenization and stopword removal using NLTK
	•	Feature Engineering:
	•	TF-IDF vectorization
	•	Model Training:
	•	Logistic Regression
	•	Random Forest Classifier
	•	Evaluation:
	•	Models evaluated using accuracy, precision, recall, and F1-score
	•	Cross-validation to ensure robust model performance

Key Findings
	•	TF-IDF vectorization combined with a Logistic Regression model produced the highest accuracy.
	•	Achieved strong precision and recall, making the model suitable for practical deployment.
	•	Predictive modeling of reviews can help The Film Junky Union quickly detect public sentiment trends and adjust marketing strategies accordingly.

(Detailed evaluation results and business recommendations are available in the notebook.)

Contributing

Contributions are welcome!
If you want to explore more advanced NLP techniques (e.g., word embeddings, deep learning models like LSTM), feel free to fork the repo and submit a pull request.

License

This project is licensed under the MIT License.

Contact

Chavez Data
GitHub: @ChavezData

⸻

Would you also like me to draft a short “Future Work” section you could add to the README?
(For example: trying deep learning models, hyperparameter tuning, or deploying as an API — looks very professional to recruiters!)
Let me know!
