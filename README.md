**Netflix Movies and TV Shows Data Analysis**
This project performs a comprehensive Exploratory Data Analysis (EDA) on the Netflix dataset to uncover trends in content production, geographical distribution, and viewer ratings. Using Python libraries like Pandas, Seaborn, and Matplotlib, the analysis provides insights into how the streaming giant's library has evolved over the years.

## Project Overview
The goal of this analysis is to understand the content dynamics on Netflix, focusing on:

Content Distribution: Comparison between Movies and TV Shows.

Top Contributors: Identifying top directors, cast members, and countries.

Temporal Trends: Analyzing release patterns over the last two decades.

Genre & Ratings: Visualizing popular genres and the distribution of content ratings (e.g., TV-MA, PG-13).

## Key Features
Data Cleaning: Handled missing values in director, cast, and country columns.

Feature Engineering: Parsed the duration column to differentiate between movie lengths (minutes) and TV show lengths (seasons).

Visualizations:

Pie Charts for rating distributions.

Bar Charts for the top 10 genres and countries.

Count Plots for comparing Movie vs. TV Show releases per year.

Word Clouds to visualize geographical content density.

## Tech Stack
Language: Python

Environment: Google Colab / Jupyter Notebook

Libraries: * NumPy & Pandas: Data manipulation and cleaning.

Matplotlib & Seaborn: Data visualization.

WordCloud: Text data visualization.

## Insights from Data
Content Type: Netflix hosts significantly more Movies than TV Shows.

Top Production Hub: The United States leads in content production, followed by India and the United Kingdom.

Average Duration: The average movie length is approximately 99.5 minutes, while the average TV show lasts about 1.76 seasons.

Top Actor: Anupam Kher is the most frequent cast member in the dataset.

## How to Run
Clone this repository:

**Bash**
git clone https://github.com/your-username/netflix-analysis.git
Install the required dependencies:

**Bash**
pip install pandas numpy matplotlib seaborn wordcloud
Open the .ipynb file in Google Colab or Jupyter Notebook.

Ensure the dataset netflix_movies.csv is in the same directory as the notebook.

## Dataset
The dataset used in this project includes information on all movies and TV shows available on Netflix as of 2021, including details like cast, director, ratings, release year, and duration.
