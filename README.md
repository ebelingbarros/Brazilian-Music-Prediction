## Predicting Brazilian music from Spotify Playlists with Unsupervised Machine Learning
A project by [Francisco Ebeling](https://github.com/ebelingbarros).

![Picture](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/pic06brasil.jpg)

## Contents:

- [The project](#The_project)
- [The files](#The-files)
- [Visualizations and results](#Visualizations-and-results)

***


## The project
In this project, a music predictor for musics from Spotify playlists for Braziliam music is developed building on an unsupervised Machine Learning model. Playlist information from Spotify's is gathered for four musical genres (Sertanejo, Funk, Pagode, Pop), and is used as input for an unsupervised Klearn machine learning modelling. 
Building on 8 features from Spotify registered songs (danceability,	energy,	loudness,	speechiness,	acousticness,	instrumentalness,	liveness and valence) plus a genre dummy, 20 clusters are generated. This input is transformed into a .csv file that is used as data for a music predictor. In what follows the files generated throughout the process and some insights drawn from graphs are presented, one of which from Tableau.

## The files
- Gathering playlist songs from Spotify's API: [Jupyter Notebook](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/gathering_playlists.ipynb)
- Unsupervised clustering model: [Jupyter Notebook](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/model_unsupervised.ipynb) 
- The music recommender: [Jupyter Notebook](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/music_recommender.ipynb) 
- Some insights through data visualizations: [Jupyter Notebook](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/data_insights.ipynb) 
- A Tableau dashboard with graphs: [Story](https://public.tableau.com/views/Brazilianmusicprediction-featuresclustered/Story1?:language=de&:display_count=y&publish=yes&:origin=viz_share_link) 


## Visualizations and results

![Picture](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/feats_music.png)


![Picture](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/histogram.png)


![Picture](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/tableau_viz.png)


