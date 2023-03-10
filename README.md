# Movie-Recommendation-System

## Short description

**Content-Based Movie Recommendation System:** An implementation using Python and NLTK to build a movie recommendation system based on features like plot, actors, genre, director, producers, production companies, and user ratings.


## Detailed description


This project aims to build a content-based movie recommendation system using Python and NLTK. The recommendation system utilizes features such as plot, actors, genre, director, producers, production companies, and user ratings to provide users with accurate and tailored movie recommendations that match their preferences and watching history.

The system leverages Natural Language Processing (NLP) techniques using NLTK, along with machine learning models such as cosine similarity,Tfidf, CountVectorizer, and TfidfVectorizer to extract, process, and measure similarity between movies' features and make effective recommendations to users. With these features, the system can provide recommendations that closely match a user's interests and provide them with options to explore and discover new movies that they might enjoy.

In this project, we start by exploring the dataset; preprocessing, extracting and vectorizing features, training a few recommendation models utilising NLP techniques like TF-IDF along with Cosine similarity, and tuning hyperparameters to achieve the most accurate recommendations possible. We then evaluate our models on their ability to provide accurate and meaningful recommendations utilizing appropriate evaluation metric.

This repository contains all the code, data, and results for the movie recommendation system. Due to the large size of the data and the limited storage of github, the dataset can be found with this [link](https://drive.google.com/drive/folders/1ogZUmVyVTL6YmvZM3HTyNODzYTT3p8xm?usp=sharing).


## Result

Two models were built. They were both asked to generate recommendations or movies similar to Spider-Man 3. Here are the recommendations and cosine similarities of the two models:

Model 1:

![Alt Text](https://github.com/GbengaLadapo/Movie-Recommendation-System/blob/3a1385c727c29a66fa50c9e88bfef2d1f7045633/model%201.png)

Model 2:

![Alt Text](https://github.com/GbengaLadapo/Movie-Recommendation-System/blob/173f1c2eea3868ad17169cbe73c9bce3b0f40e95/model%202.png)


In comparing the recommendations of the two recommendation models for movies similar to Spider-Man 3, we can see that Model 1's suggestions, such as "Not Easily Broken" and "Arachnophobia," lacks accuracy as they are actually drama/romance and horror movies, respectively, both lacking similarity to Spider-Man 3. Even though "Arachnophobia" contains keyword Spider, it doesn't share general similarity in perspective of genre or plot. In contrast, Model 2 recommends more accurate choices, such as Hulk, which shares similar genre, plot, and other features like a Superhero movie. Therefore, **Model 2 is a more accurate and effective recommendation model.**
