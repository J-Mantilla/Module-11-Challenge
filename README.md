# Module-11-Challenge
Mars News and Weather Scraping Project
Overview
This project is divided into two main parts:

Scraping Mars News Titles and Preview Text
Scraping and Analyzing Mars Weather Data
The objective of this project is to practice web scraping techniques using Beautiful Soup and automated browsing tools. The data scraped from the Mars News site and the Mars Temperature Data site will be stored in Python data structures and Pandas DataFrames for further analysis.

Part 1: Scrape Titles and Preview Text from Mars News
Instructions

Open the Jupyter Notebook: part_1_mars_news.ipynb.
Use automated browsing to visit the Mars News Site.
Inspect the webpage to identify elements containing news titles and preview text.
Create a Beautiful Soup object to parse the HTML content of the webpage.
Extract the titles and preview text of the news articles.
Store the scraping results in Python data structures:
Each title and preview text pair should be stored in a dictionary with two keys: title and preview.

Part 2: Scrape and Analyze Mars Weather Data
Instructions

Open the Jupyter Notebook: part_2_mars_weather.ipynb.
Use automated browsing to visit the Mars Temperature Data Site.
Inspect the webpage to identify elements containing the weather data.
Create a Beautiful Soup object to parse the HTML content of the webpage.
Scrape the data from the HTML table into a Pandas DataFrame.
Ensure the DataFrame columns have the following headings:
id: Identification number of a single transmission from the Curiosity rover
terrestrial_date: Date on Earth
sol: Number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: Solar longitude
month: Martian month
min_temp: Minimum temperature, in Celsius, of a single Martian day (sol)
pressure: Atmospheric pressure at Curiosity's location
Examine the data types associated with each column and convert them to the appropriate types (datetime, int, float), if necessary.
