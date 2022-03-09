# Scraping Top 1000 IMDb movies

## Introduction
IMDb is an online database of information related to films, television programs, home videos, video games, and streaming content online – including cast, production crew and personal biographies, plot summaries, trivia, ratings, and fan and critical reviews.

Almost all of us, at some point in time have looked up for a movie's/show's reviews and ratings on IMDB, to decide if we want to go ahead with watching it or not.

As of December 2020, IMDb has approximately 7.5 million titles (including episodes) and 10.4 million personalities in its database, as well as 83 million registered users.

## Project Description: 
Created a dataset of Top 1000 movies by scraping the IMDb site and wrote it to a CSV file, performed data scrubbing techniques, detecting & imputing missing values, handling inconsistent data. 

## Steps:
* Download the webpage using requests
* Parse the HTML source code using BeautifulSoup library and extract the desired infromation
* Building the scraper components
* Compile the extracted information into Python list and dictionaries
* Converting the python dictionaries into Pandas DataFrames
* Write information to the final CSV file

## Packages Used:
* Requests — For downloading the HTML code from the IMDB URL
* BeautifulSoup4 — For parsing and extracting data from the HTML string
* Pandas — to gather my data into a dataframe for further processing
