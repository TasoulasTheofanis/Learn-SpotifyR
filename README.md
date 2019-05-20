# Learn-SpotifyR
SpotifyR is library for R that makes possible the crawl of interesting metadata from artist's songs from Spotify.

## How about a video with the explaination of the code? 
[![the video](https://i9.ytimg.com/vi/IQQFeKs5eWo/maxresdefault.jpg?sqp=CPDMi-cF&rs=AOn4CLA8KSgzbUSJOWnR0jQ91WDgoBFEZA&time=1558374031289)](https://youtu.be/vt5fpE0bzSY)

## In a nutshell

#### 1) install.packages('spotifyr')

#### 2) library(spotifyr)

#### 3) Sys.setenv(SPOTIFY_CLIENT_ID = ' Your own client id from spotify dashboard')
####  Sys.setenv(SPOTIFY_CLIENT_SECRET = 'Your own client secret from spotify dashboard')
####  access_token <- get_spotify_access_token()
   
#### 4) artist.audio.features <- get_artist_audio_features('Name of an artist') 

Then you can do some cool music data analysis
