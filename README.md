# imdb
Find IMDB Ratings
This script is used to fetch the Ratings and Genre of the films in your films folder that match with ones on IMDb, the data is scraped from IMDB's official website and store in a csv file. The csv file can be used for analysis then, sorting acc to rating etc.

Input: -> Path of the directory which contains the films.

Output: -> A new csv file is made - 'film_ratings.csv' which contains the ratings for the films in your directory.

Prerequisites
This program uses and external dependency of 'BeautifulSoup' (for web scraping), 'requests' (for fetching content of the webpage), 'pandas' (to make the csv file), 'os' (to get data from directory).
These libraries can be installed easily by using the following command: pip install -r requirements.txt

How to run the script
-> Install the requirements.
-> Inside the find_IMDb_rating.py, update the directory path.
-> Type the following command: python find_IMDb_rating.py
-> A csv file with rating will be created in the same directory as the python file.
