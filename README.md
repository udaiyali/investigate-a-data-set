udacity-Investigate a Data set

Udacity Data Analyst Project: Investigate a Dataset (TMDb movie data)
In this project, I analyzez a dataset and communicated my findings about it. The libraries which I used were Python libraries NumPy, Pandas, and Matplotlib to do the analysis

First some Data Wrangling was applied, before the data was cleaned in order to perform Exploratory Data Analysis.

How to run the script
You can run the script using a Python integrated development environment (IDE). This script is written in Python 3, so you will need the Python 3.x version of the installer. The code was written in Jupyter Notebook.

Datasets
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters. The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

Variables:

id
imdb_id
popularity
budget
revenue
original_title
cast
homepage
director
tagline
keywords
overview
runtime
genres
production_companies
release_date
vote_count
vote_average
release_year
budget_adj
revenue_adj
Files
tmdb-movies.csv

Questions to answer
1) How has the popularity of drama movies changed over decades?
1.a) Number of movies released in each decade - Gener Drama
1.b. Predict the production house which will produce drama movies having high popularity.
2) Are older movies more popular?
3) Most popular genres.
4) Total Revenue vs Release year.

Findings

The most popular gener, Drama had been throughly analyzed and it can be seen that the popularity for drama movies year on year had been fluctuation but overall they are the most popular. We can alos see that the number of drama movies released had doubled every decade except for the last one.
The three production companies which produced movies that are popular among the viewers. Hence we can saftley say the movie produced by theses companies would be popular but this is an assumption from the past data. The companies are
Paramount Pictures
Universal Pictures
Columbia Pictures
We also saw the popularity of movies. As the movie industry got bigger so did the popularity. Hence from the results we can see that the newer movies are much popular among the viewres that the old movies. From the last data analysis, we can also see that the revenue for newer movies are much higher than the older movies.
The most popular geners among the viewers are Drama which is closly followed by Comedy.

All results are limited to the underlying data set and as no advaned statistics were performed, the results can only be treated as indicators and are not generalizable. Furthermore, one has to consider that many entries in the dataset have been removed due to missing data
