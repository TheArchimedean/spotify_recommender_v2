# spotify_recommender_v2
A Spotify song recommending project using Spotify Web API audio features as well as the TF-IDF algorithm on genre information. 

The project originally began on DeepNote, as can be seen in `spotify-song-recommender-features` but on the free plan, the cloud machine simply did not have enough RAM to run what I wanted to do. Having a powerful home PC, I instead exported the `.ipynb` file and ran it in a Jupyter notebook. There were multiple problems with that, as I had been using DeepNote's DataFrame SQL feature to query straight from the `.csv` as if it was a database, which was very useful in joining the 'tables' (each `.csv` file) on the artist name column near the end.

Once I had branched off into using Jupyter, I made a new notebook, `spotify-song-recommender-model` to run the TF-IDF algorithm and generate song recommendations. 

Thus to run this project, it would be better to see the code on my [shared DeepNote article]('https://deepnote.com/@tedspace/Spotify-Song-Recommendation-System-v20-6db3d211-80b9-4bca-86b0-008e23f55791'). Then once the `complete-feature-set.csv` file has been generated, the `model` notebook can be ran as normal.
