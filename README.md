# Sens Critique Machine Learning Project

## Description

This machine learning project aims to predict the popularity of movies by developing a custom algorithm from a non-existing database. The exercise involves working with various data tools to create a machine learning model based on data values generated from scratch.

**Objective: Create an algorithm to predict the popularity of a movie.**

---

## Data Collection

To predict the popularity of movies, data was extracted from four types of websites:

1. [Top 111 Films](https://www.senscritique.com/films/tops/top111)
2. Movie description websites
3. Technical details of each movie's website
4. Director websites

Python's BeautifulSoup library was utilized for web scraping. The information extracted includes:

- French titles
- Ratings by users
- Duration of films
- Genres
- Release date
- Director information
- Production details
- Viewer engagement metrics
- Director popularity and directed movies' ratings

## Data Cleaning and Transformation

During the cleaning process, the steps included:

- Extracting relevant information
- Converting data types
- Handling missing values
- Creating dummy variables for movie genres
- Standardizing currency to USD
- Extracting country information from movie details

The resulting dataset comprises essential features such as movie details, viewer engagement metrics, production details, and director-related information.

## Machine Learning Model

The dataset was merged and processed to form the final dataset for machine learning. Columns include:

- Title of the movie
- Ratings by website users
- Release date
- Duration in minutes
- Genre dummies
- Viewer engagement metrics (votes, want-to-see, favourites, comments)
- Country of movie production
- Film distributor
- Budget in USD
- Director information (name, popularity, directed movies' average ratings)

The dataset is now ready for building and training a machine learning model to predict movie popularity.

---

*Note: The machine learning model creation and training steps are not included in this code snippet.*
