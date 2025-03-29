IMDb Movie Dataset - Exploratory Data Analysis (EDA)

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the IMDb movie dataset to uncover trends, patterns, and insights related to movie ratings, budgets, gross revenue, and more. The dataset includes various attributes such as movie titles, genres, runtime, ratings, votes, budget, gross revenue, and director details.

📂 Dataset Information

The dataset contains the following columns:

id - Unique identifier for each movie

primaryTitle - Official movie title

originalTitle - Original title of the movie

isAdult - Indicates whether the movie is for adults (1 = Yes, 0 = No)

runtimeMinutes - Duration of the movie in minutes

genres - Genres associated with the movie

averageRating - IMDb average rating (scale of 1 to 10)

numVotes - Number of votes received on IMDb

budget - Estimated budget for the movie

gross - Total gross revenue earned

release_date - Release date of the movie

directors - Names of the directors

🔍 Key Explorations & Insights

Rating Distribution: Identified high and low-rated movies with outlier analysis.

Budget vs. Gross Revenue: Explored how budget influences box office performance.

Director Analysis: Identified top-rated and highest-grossing directors.

Genre Analysis: Evaluated which genres perform best in ratings and revenue.

Outlier Detection: Used boxplots to visualize extreme values in budget, gross revenue, and ratings.

🛠️ Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook for analysis and visualization

Git & GitHub for version control

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/imdb-eda.git

Navigate to the project directory:

cd imdb-eda

Install dependencies:

pip install -r requirements.txt

Open the Jupyter Notebook:

jupyter notebook

📊 Visualizations

This project includes various bar plots, scatter plots, and boxplots to analyze different aspects of the dataset.

📎 Future Enhancements

Perform predictive modeling to forecast a movie’s success based on features.

Analyze trends over time in movie budgets, ratings, and earnings.

Use machine learning models for movie rating predictions.

📢 Contributing

Feel free to fork the repository, raise issues, and submit pull requests to improve the analysis.

📜 License

This project is open-source and available under the MIT License.
