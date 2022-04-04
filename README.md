# Data-Mining

## Project 1 - Movie Recommendations
The dataset of this project contains Netflix movies.
 - [Project Implementation](https://github.com/giannhskp/Data-Mining/blob/main/Project1.ipynb)
 - [Project Description](https://github.com/giannhskp/Data-Mining/blob/main/1st-Assignment-2021.pdf)

#### Part 1
In the first part of the project we observe the dataset and produce statistics about the content of the dataset.
Some of the statistics are:
  - Number of movies/series.
  - Country with the most content.
  - Year with the most content.
  - The popularity of each genre for every country.

#### Part 2
We implement a recommendation system in order to recomend similar movies to a given movie.
In order to represent each movie we tried the two following representations:
  - [Bag Of Words (BoW)](https://en.wikipedia.org/wiki/Bag-of-words_model)
  - [TF-IDF](https://en.wikipedia.org/wiki/Tf%E2%80%93idf)

In order to compute the similarity between the repsesentations we used:
  - [Jaccard-Tanimoto coefficient](https://en.wikipedia.org/wiki/Jaccard_index)
  - [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity)

PS: if the notebook cannot be opened on github, you can view it via the Jupiter nbviewer:
  - Visit: https://nbviewer.org/
  - Paste the link of the notebook (https://github.com/giannhskp/Data-Mining/blob/main/Project1.ipynb)

## Project 2 - Fake/True News Classification

 - [Project Implementation](https://github.com/giannhskp/Data-Mining/blob/main/Project2.ipynb)
 - [Project Description](https://github.com/giannhskp/Data-Mining/blob/main/2nd-Assignment-2021.pdf)


Given a dataset with news articles we should train a model that classifies each article as fake or True.
We try different ways to represent the text of each article, such as:
  - Bag Of Words 
  - TF-IDF
  - Word2Vec

Also, we use different models in order to compare their performance.
The models that we used are:
  - Logistic Regression
  - Naive Bayes
  - Support Vector Machines (SVM)
  - Random Forest

Finaly we compare the performance between every combination of representation/model.
