
# Classify Song Genres from Audio Data

Over the past few years, streaming services with huge catalogs have become the primary means through which most people listen to their favorite music. But at the same time, the sheer amount of music on offer can mean users might be a bit overwhelmed when trying to look for newer music that suits their tastes.

For this reason, streaming services have looked into means of categorizing music to allow for personalized recommendations. One method involves direct analysis of the raw audio information in a given song, scoring the raw data on a variety of metrics. Today, we'll be examining data compiled by a research group known as The Echo Nest. Our goal is to look through this dataset and classify songs as being either 'Hip-Hop' or 'Rock' - all without listening to a single one ourselves. In doing so, we will learn how to clean our data, do some exploratory data visualization, and use feature reduction towards the goal of feeding our data through some simple machine learning algorithms, such as decision trees and logistic regression.

To begin with, let's load the metadata about our tracks alongside the track metrics compiled by The Echo Nest. A song is about more than its title, artist, and number of listens. We have another dataset that has musical features of each track such as danceability and acousticness on a scale from -1 to 1. These exist in two different files, which are in different formats - CSV and JSON. While CSV is a popular file format for denoting tabular data, JSON is another common file format in which databases often return the results of a given query.


## Tech Stack

Python, Pandas, Numpy, Matplotlib, Sklearn



## Roadmap

1. Preparing our dataset
2. Pairwise relationships between continuous variables
3. Normalizing the feature data
4. Principal Component Analysis on our scaled data
5. Further visualization of PCA
6. Train a decision tree to classify genre
7. Compare our decision tree to a logistic regression
8. Balance our data for greater performance
9. Does balancing our dataset improve model bias?
10. Using cross-validation to evaluate our models
