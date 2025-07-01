# Netflix_movies_Analysis
A data-driven exploration of trends, genres, and popularity in a large movie dataset using Python, Pandas, and Seaborn.

📑 Project Overview
This project analyzes a dataset of nearly 10,000 movies to uncover insights about genres, popularity, voting patterns, and trends over time. The workflow includes data cleaning, transformation, exploratory data analysis, and visualization.

📂 Dataset
Source: mymoviedb.csv

Original Rows: 9,827

Columns:

 Release_Date (Year extracted)

Title

Popularity

Vote_Count

Vote_Average (Categorized)

Genre (Exploded for multi-genre movies)

🛠️ Data Preparation
No missing or duplicate values in the dataset.

Dropped columns: Overview, Original_Language, Poster_Url (not needed for analysis).

Converted Release_Date to year only.

Categorized Vote_Average into:

not_popular

below_avg

average

popular

Split and exploded Genre so each row represents a single genre per movie.

Final shape after cleaning:

Rows: 25,552

Columns: 6

🔍 Key Questions & Insights
1. What is the most frequent genre?
Drama is the most frequent genre, appearing in over 14% of entries.

2. Which genres have the highest votes?
Drama again has the highest popularity among fans, with more than 18.5% of movies in the “popular” category.

3. Which movie is the most popular?
Spider-Man: No Way Home (2021)

Genres: Action, Adventure, Science Fiction

Popularity Score: 5083.954

4. Which movie is the least popular?
The United States vs. Billie Holiday (2021) and Threads (1984)

Genres: Music, Drama, History, War, Science Fiction

Popularity Score: 13.354

5. Which year had the most movie releases?
2020 had the highest number of movies released.

📊 Visualizations
Genre Distribution:
Drama is the most common genre.

Vote Average Distribution:
Shows the breakdown of movies by popularity categories.

Release Year Histogram:
Reveals the most prolific years for movie releases.

🚀 How to Run
Clone this repository and place mymoviedb.csv in the root directory.

Install dependencies:

bash
pip install pandas matplotlib seaborn numpy
Run the analysis notebook or script.

🧩 Dependencies
Python 3.x

pandas

matplotlib

seaborn

numpy

📚 Conclusion
This project reveals fascinating trends in movie genres, popularity, and voting patterns.
Drama dominates both in frequency and popularity, while 2020 stands out as a prolific year for movie releases.

