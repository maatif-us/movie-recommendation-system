# Movie Recommendation Algorithm Application
This application provides a simple movie recommendation algorithm based on user ratings. It uses the Surprise library for collaborative filtering and provides recommendations for movies that a user might like based on their past ratings.

### Dataset
The dataset used for this application consists of two files:

1. ratings.csv: Contains user ratings for movies.
2. movies.csv: Contains movie titles and genres.
   
### Usage
- **Load the Dataset:** Use pandas to load the ratings.csv and movies.csv files into DataFrames.
- **Split the Data:** Split the ratings data into training and testing datasets based on user IDs.
- **Train the Model:** Use the Surprise library to train a recommendation model using collaborative filtering (SVD algorithm).
- **Make Recommendations:** Given a user ID, use the trained model to recommend movies for that user.
- **Evaluate the Model:** Calculate the RMSE (Root Mean Squared Error) to evaluate the model's performance.

### Dependencies
- pandas
- scikit-learn
- Surprise
