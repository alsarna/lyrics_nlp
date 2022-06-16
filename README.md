# lyrics_nlp

Analysis of lyrics using natural language processing methods\
Data - lyrics of songs from Billboard year-end charts from years 1950 - 2021
1. data_preprocessing - getting metadata from billboard API, lyrics from genius API and audio_features from spotify API
2. lyrics_data_processing - NLP actions: tokenization, lemmatization, creating corpus
3. lyrics_analysis - creating word clouds, most popular words, bad words classification, most popular bad words, sentimental analysis, statistics for artists and songs, topic identification
4. spotify_data_analysis - music genres and audio features, analysis, histograms
5. hit prediction - downloading current week chart from billboard and spotify and predicting hits for last week billboard chart using model trained on data from 1950 - 2021