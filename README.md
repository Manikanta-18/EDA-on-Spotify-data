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


## Data Import & Initial Understanding

- The dataset was loaded using the Pandas library to begin the exploratory data analysis process.  
- Initial inspection was performed to understand the structure and quality of the data.

### Initial Checks
- Examined the dataset shape to understand the number of records and features
- Reviewed column names to identify available variables
- Checked data types to distinguish between numerical and categorical features
- Analyzed missing values to assess data completeness

## Data Preprocessing
- Handled null values
- Ensured numerical columns were correctly formatted for analysis and visualization
- Created total playlist and total chart counts across all platforms.

## Key takeaways from EDA
- The correlation between total chart presence and streams is weakly positive (r = 0.13), indicating that chart visibility has a limited impact on streaming volume.
- The distribution shows that C♯ is the most common musical key among popular songs, while D♯ is the least frequent, indicating a strong preference for certain tonalities in commercially successful tracks.
- Although BPM values range from 65 to 180, 50% of highly danceable songs are concentrated between 100 and 135 BPM, indicating that moderate tempos are most conducive to danceability.
- Around 72% of tracks fall within the 50–90% energy range with danceability above 50%.
  

