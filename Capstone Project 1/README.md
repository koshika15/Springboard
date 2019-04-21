# Predicting IMDB Ratings

Today’s movie watcher is spoilt for choice with increase in movie streaming platforms, DVD rental services and easy access to movie theatres. Knowing a movie’s rating before watching the movie helps reduce the decision fatigue arising out of increased options. IMDb (Internet Movie database) is often a go-to source for knowing a movie’s ratings, user reviews, plot, casting and other details before watching that movie. The ratings in IMDb are a function of the ratings given by the users.

But unfortunately, IMDb allows users to provide ratings and reviews only after movie release. So, if you want to select a movie for a first day show, you don’t have the ratings to rely on.

## Dataset used

The dataset to be used in the project has been acquired from IMDB website from the link: https://www.imdb.com/interfaces/.
IMDB has 6 relevant datasets contained in separate gzipped, tab-separated-values (TSV) formatted files. These datasets have details of all the movies, tv episodes, documentaries etc for all countries of the world.

## Detailed Process
To understand the whole process these links can be followed in order:

[Data Wrangling](https://github.com/koshika15/Springboard/blob/master/Capstone%20Project%201/B.%20Data_wrangling.ipynb)

[Data Story](https://github.com/koshika15/Springboard/blob/master/Capstone%20Project%201/C.%20Data_Story.ipynb)

[Statistical Inference](https://github.com/koshika15/Springboard/blob/master/Capstone%20Project%201/D.%20EDA.ipynb)

[Machine Learning](https://github.com/koshika15/Springboard/blob/master/Capstone%20Project%201/E.%20Machine%20Learning.ipynb)

## Project Report
Click [here](https://github.com/koshika15/Springboard/blob/master/Capstone%20Project%201/Capstone%20Project%201_%20Final%20Report.pdf) for the full project report.

## Result
The objective of this project was to predict the IMDB rating of movies before they are released. The model we came up with gives us good results for movies rated between 4 and 8, most of them within ± 1 error. For the extreme ratings though, we are getting larger error which is mostly within ±2 error points.
