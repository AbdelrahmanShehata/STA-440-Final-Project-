
# Data Dictionary for Spotify Tracks Dataset

This dataset contains information about various tracks on Spotify, tracking their performance in charts, features derived from Spotify's audio analysis, and other metadata. Below is a detailed description of each column in the dataset.

- **Unnamed: 0**: This appears to be a unique identifier for each row.
- **title**: The title of the track.
- **rank**: The ranking of the track on the chart for a given day.
- **date**: The date on which the ranking was recorded.
- **artist**: The name of the artist(s) of the track.
- **url**: The URL to the track on Spotify.
- **region**: The region in which the track was charted.
- **chart**: The chart in which the track appears (e.g., top200).
- **trend**: Indicates the movement of the track's position compared to the previous ranking (e.g., MOVE_UP, MOVE_DOWN, SAME_POSITION).
- **streams**: The number of times the track was streamed.
- **track_id**: Spotify's unique identifier for the track.
- **album**: The album or collection to which the track belongs.
- **popularity**: A measure of the track's popularity at the time of data collection.
- **duration_ms**: The length of the track in milliseconds.
- **explicit**: Indicates whether the track contains explicit content (TRUE or FALSE).
- **release_date**: The date on which the track was released.
- **available_markets**: Array of market codes where the track is available.
- **af_danceability**: Danceability describes how suitable a track is for dancing based on a combination of musical elements.
- **af_energy**: Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity.
- **af_key**: The estimated overall key of the track.
- **af_loudness**: The overall loudness of a track in decibels (dB).
- **af_mode**: Modality of the track, major (1) or minor (0), indicating the tonality.
- **af_speechiness**: Speechiness detects the presence of spoken words in a track.
- **af_acousticness**: A confidence measure of whether the track is acoustic.
- **af_instrumentalness**: Predicts whether a track contains no vocals.
- **af_liveness**: Detects the presence of an audience in the recording.
- **af_valence**: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track.
- **af_tempo**: The overall estimated tempo of a track in beats per minute (BPM).
- **af_time_signature**: An estimated overall time signature of a track.
