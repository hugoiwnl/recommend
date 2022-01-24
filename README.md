# Recommendation system
- This is a movie recommendation system. Details about the movie data can be found in "/data/readme.txt".
- The system starts with classes for reading ratings and movies, and preparing appropriate data for further processing.
- We have a recommender class that takes in a predictor and returns recommendations for a user, depending on the predictor used. We can also evaluate these predictions with the evaluate method.
- There are multiple predictors like, Average predictor, Item Based predictor(adjusted cosine similarity is used to calcualte the similarity between items), Slope One prediction.
- In the *"Recommendation for myself"* section, I have rated some movies, and with the Item Based Predictor I got recommendations, and some of the recommendations are movies that I have seen and I did liked.
- The last section *"Evaluation method"*, is where different predictors are evaluated and comparared.
