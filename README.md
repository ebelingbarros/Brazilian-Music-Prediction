## Predicting Brazilian music from Spotify Playlists with Unsupervised Machine Learning
A project by [Francisco Ebeling](https://github.com/ebelingbarros).

![Picture](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/pic06brasil.jpg)

## Contents:

- [The project](#The_project)
- [The files](#The-files)
- [Some visualizations](#Some-visualizations)

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


## Some visualizations

The following 4 plots display charactersitics of the 235 songs from the sample. Songs 1 to 65 are from the genre "Sertanejo", 66 to 115 from the genre "Funk", 116 to 118 from "pagode" and 186-235 from the genre "pop". As can be seen, there is clear evidence that the genres "Funk" and "Pop" are the more danceable ones. The more energetic songs are from the Sertanejo and Funk genres, but some of the first's songs are less energetic. This probably reflects the fact that they are more romantic songs. The "loudness" plot shows that while Funk songs are the loudest, those from Pagode are quieter.

![Picture](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/feats_music.png)

The following graph plots the clusters found by the model:

![Picture](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/histogram.png)

In this Tableau visualization, the features "energy" and "danceability" are plotted according to the respective clusters.

![Picture](https://github.com/ebelingbarros/Brazilian-Music-Prediction/blob/main/tableau_viz.png)


