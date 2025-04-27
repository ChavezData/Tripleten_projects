Data Collection and Storage (SQL) - Movie Database Project

A project demonstrating data collection, storage, and querying skills using SQL on a relational movie database.

Table of Contents
	•	About
	•	Dataset
	•	Project Objectives
	•	Technologies Used
	•	How to Run
	•	Key Concepts
	•	Key Insights
	•	Contributing
	•	License
	•	Contact

About

In this project, I performed SQL-based data collection and analysis on a relational database containing movie-related information.
The goal is to practice working with multiple related tables, writing optimized SQL queries, and extracting insights for business use cases in the entertainment industry.

The project involved:
	•	Database exploration
	•	Complex queries with joins, groupings, and subqueries
	•	Data aggregation and filtering
	•	Answering specific business questions

Dataset

The relational database includes tables such as:
	•	movies (movie titles, release year, etc.)
	•	genres (genre names)
	•	directors
	•	ratings
	•	financials (budget and revenue)

(Data provided as part of the TripleTen curriculum.)

Project Objectives
	•	Explore the movie database structure
	•	Write efficient SQL queries to answer business questions
	•	Perform data aggregation and multi-table joins
	•	Extract meaningful statistics such as top-grossing movies, most common genres, and rating distributions

Technologies Used
	•	SQL (PostgreSQL syntax)
	•	Jupyter Notebook (to run SQL queries via a Python connector)
	•	Pandas (for displaying query outputs)

How to Run
	1.	Clone the repository:

git clone https://github.com/ChavezData/Tripleten_projects.git

	2.	Navigate to the project directory:

cd Tripleten_projects/Data_Collection_and_Storage(SQL)

	3.	Open the notebook:

You can open Project 6_Data_Collection_and_Storage(SQL).ipynb with Jupyter Notebook or Google Colab.
	4.	Make sure you have the following libraries installed:

pip install pandas sqlalchemy psycopg2

	5.	(Optional) Set up a local SQL database if you want to recreate the environment and run queries yourself.

Key Concepts
	•	SQL Joins: Combining data from multiple tables
	•	Grouping and Aggregation: Calculating averages, sums, counts, etc.
	•	Subqueries: Writing nested queries to simplify complex logic
	•	Filtering and Ordering: Extracting targeted insights based on business needs

Key Insights
	•	Identified top-performing genres based on box office revenue.
	•	Analyzed rating trends across different movie categories.
	•	Determined the correlation between production budgets and gross revenue.
	•	Uncovered directors with the highest average ratings.

(Detailed answers and query outputs are available in the notebook.)

Contributing

Contributions are welcome!
If you’d like to expand the project (e.g., more advanced queries, database optimization techniques), feel free to fork the repo and submit a pull request.

License

This project is licensed under the MIT License.

Contact

Chavez Data
GitHub: @ChavezData
