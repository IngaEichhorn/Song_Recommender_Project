# Song Recommender Project

## Part A:

Create a function to scrape the Billboards 100 HOT songs and create a local dataframe of songs with them including:
 - Song’s name
 - Song’s artist
 - Rank
 
File: Scraper_Music_Info_billboard.ipynb

Create a function that uses an user input song as a reference to randomly recommend a song of the billboard top 100

File: Hot_Music_Recommender.ipynb


## Part B:

Using Spotipy, scrape as many song infos (artist, track, id) and features:

  Mood: Danceability, Valence, Energy, Tempo
  
  Properties: Loudness, Speechiness, Instrumentalness
  
  Context: Liveness, Acousticness
  
Size of the dataset: 21,391; without duplicates: 20290

File(s): Scraper_Music_features_SpotifyPlaylists.ipynb; features_df.csv to features_df11.csv

Size of the large dataset: 222,313

File: Data/large_musicset.csv



Cluster data according to their music features using StandardScaler and k-Means Clustering

Music dataset: 8 clusters

File: Music_k_means_clustering.ipynb

Large Music dataset: 10 clusters

File: Large_Music_k_means_clustering.ipynb


Build Music Recommender based on clustered music dataset using the user input song as a query for spotify, returning user song features.

The user songs cluster is determined based on music features and a sample song of the same cluster is recommended to the user, including a listening sample (spotify player).

File: Actual_Music_recommender.ipynb

Using the clustered large music dataset: Large_Music_Actual_recommender.ipynb
