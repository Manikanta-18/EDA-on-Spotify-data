## Dataset Overview

This dataset contains information on **953 popular music tracks**, capturing both **platform performance metrics** and **audio features**. It is designed to analyze how musical characteristics relate to a track’s popularity across major music streaming platforms.

## Track & Artist Information
- `track_name` – Name of the song  
- `artist(s)_name` – Artist or artists associated with the track  
- `artist_count` – Number of artists involved in the track  

## Release Details
- `released_year` – Year of release  
- `released_month` – Month of release  
- `released_day` – Day of release  

## Popularity & Platform Presence
The dataset tracks song visibility and performance across multiple platforms:
- `streams` – Total number of Spotify streams  
- `in_spotify_playlists` – Number of Spotify playlists featuring the track  
- `in_spotify_charts` – Presence in Spotify charts  
- `in_apple_playlists` – Apple Music playlist appearances  
- `in_apple_charts` – Apple Music chart appearances  
- `in_deezer_playlists` – Deezer playlist appearances  
- `in_deezer_charts` – Deezer chart presence  
- `in_shazam_charts` – Shazam chart presence  

## Audio & Musical Features
Each track includes key musical attributes used for audio analysis:
- `bpm` – Beats per minute (tempo)  
- `key` – Musical key of the track  
- `mode` – Major or Minor mode  
- `danceability_%` – Suitability for dancing  
- `energy_%` – Intensity and activity level  
- `valence_%` – Positiveness of the track  
- `acousticness_%` – Presence of acoustic elements  
- `instrumentalness_%` – Likelihood of no vocals  
- `liveness_%` – Presence of live audience elements  
- `speechiness_%` – Amount of spoken words  

## Dataset Size
- **Rows:** 953 tracks  
- **Columns:** 24 features  

