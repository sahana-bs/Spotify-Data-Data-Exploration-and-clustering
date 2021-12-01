# Spotify-Data-Data-Exploration-and-clustering
Final project for CS4824 Machine Learning class Fall'21.
Dataset [source](https://www.kaggle.com/lilycarew/spotify-songs-information).
<br>
This can be seen as a genre classification problem. But it has 9 classes and the number of samples are very insignificant (after pre-processing it is around 9k) for a decent multiclass classifier. So we cluster this data to understand the patterns and which attributes influence a song to be grouped into a cluster. <br>

Also, spotify api does not [(still)](https://community.spotify.com/t5/Spotify-for-Developers/Spotify-Search-API-does-not-return-tracks-if-the-query-is-an/m-p/4971648) return the genre of a song. The only endpoint to get the genre is through the artist. But this gives the genre that an artist generally works on rather than the genre of a particular song. So, performing classification cannot be completely accurate. Hope I was able to justify why we performed clustering on this data :)
