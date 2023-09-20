# IMDb Data Scraper

This project allows you to scrape data from IMDb's Top 100 movies list and stores the information in a Pandas DataFrame. The script extracts data such as movie name, release year, runtime, IMDb rating, Metascore, number of votes, and US gross earnings (if available).

## Prerequisites

Before running the script, make sure you have the following libraries installed:

- `requests`
- `beautifulsoup4`
- `pandas`
- `numpy`

You can install these libraries using pip:

```bash
pip install requests beautifulsoup4 pandas numpy
```

## Output
The script will generate a Pandas DataFrame with the following columns:

movie_name: The name of the movie.
movie_year: The year of release.
movie_runtime: The duration of the movie.
imdb_ratings: IMDb rating of the movie.
metascore: Metascore rating of the movie (if available).
number_votes: The number of votes or ratings.
us_gross_millions: US gross earnings in millions (if available).



