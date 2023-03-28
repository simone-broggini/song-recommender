# Song Recommender

#### This project is a song recommender system based on audio features of songs. It uses Spotify's Web API to fetch audio features of songs and applies clustering techniques to group similar songs together.

The song recommender system works as follows:

1. Fetch audio features of songs using Spotify Web API
2. Apply feature engineering techniques (e.g., PCA) to reduce dimensionality and identify important features
3. Apply clustering algorithms (e.g., K-means) to group similar songs together
4. Receive input of a seed song from the user
5. Recommend similar songs based on the cluster of the seed song

## Technologies

- Spotify Web API
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
