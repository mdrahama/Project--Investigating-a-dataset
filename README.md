# Project: Investigating a dataset
 Udacity Data Analyst Project <br>
.........................................................................
TMDb Dataset<br>
........................................................................


Overview:<br>
<br>
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue,cast,release year. <br>

The project involved data assessment and cleaning, performing EDA and drawing conclusions from the data.<br>

Technologies Used <br>
Python, Numpy, Pandas, Matplotlib, Seaborn <br>
Jupyter Notebook <br>

This was a very interesting data analysis. We came out with some very interesting facts about movies. After this analysis we can conclude following:<br>

Data Cleaning:<br>

- 'id','imdb_id','homepage','tagline', 'overview','keywords' columns were dropped.<br>
- Filling Missing numeric column values was done with column mean.<br>
- 'release_month' column was created and 'release_date' column was deleted<br>
- Finally remaining all entries with NULL was dropped from the dataset.<br>

Exploratory Data Analysis<br>

Research Question 1: ( What kinds of properties are associated with movies that have high revenues?)

Revenue is increasing little with increasing popularity, budget, vote_count but not with vote_average.<br>
Research Question 2 (Who are top 20 Actors acted in top 500 profitable films?)

The top 20 actors who acted in top 500 profitable movies. From the list of top 500 profitable movies Nichloas Case acted in 15 movies, followed by Bruce Willis who acted in 10 movies. Antonio Benderes and Nicole Kidman both acted in 9 movies and in third place combinedly.<br>
Research Question 3 (Who are top 20 Actors acted in top 500 popular films?)

From the list of top 500 popular movies Malcomn McDowell, Gene Hackman, Vincent Prince & Joan Sims all acted in 4 movies.<br>
Research Question 3 (Who are top 20 Actors acted in top 500 most voted films?)

From the list of top 500 most voted movies Christopher Lee, Peter Cushing and Charles Hawtrey are in top 3 actors who acted in most of ilms in the list.<br>
Research Question 3 (Who are top 3 Genres based on popularity(top 500), profit(top 500) and runtime(top 500)?]) Top 3 Generes Based on:

Profit: Darama, Action, Thriller <br>
Profit: Comedy, Darama, Horror <br>
Runtime: Animation, Family, Comedy <br>
Limitations: Revenue was taken from actual revenue, not adjusted revenue. <br>
