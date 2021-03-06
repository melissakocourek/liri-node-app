# liri-node-app

LIRI is a Language Interpretation and Recognition Interface.

## Overview

This is a command line app that queries the spotify API, OMDB API and Bands in Town API and neatly returns to users information about their requested film, band, or movie.

## What Each Command Does
LIRI searches **Bands in Town** for concerts, **Spotify** for songs, and **OMDB** for movies


## 1.concert-this
 node liri.js concert-this <artist/band name here>
 This will search the Bands in Town Artist Events API for an for an artist and render the following information about each event to the terminal:
* Name of the venue
* Venue location
* Date of the Event (use moment to format this as "MM/DD/YYYY")
![image](https://user-images.githubusercontent.com/46450079/55568606-9cc1bf80-56c5-11e9-8b15-d710e2544f5e.png)
Video: https://drive.google.com/file/d/1xOYgKfHHKfa1I_CymxsXvLGnPD1QvDPR/view?usp=sharing

## 2.spotify-this-song
This will show the following information about the song in your terminal/bash window:

* Artist(s)
* The song's name
* A preview link of the song from Spotify
* The album that the song is from

![GitHub Logo](https://user-images.githubusercontent.com/46450079/55567435-45225480-56c3-11e9-9cbc-092f972b9c00.png)

Video:
https://drive.google.com/file/d/1cw_ZowqNajcQe9R8UpIJUqefWrBMoP0g/view?usp=sharing




## 3. movie-this

This will output the following information to your terminal/bash window:
* Title of the movie.
* Year the movie came out.
* IMDB Rating of the movie.
* Rotten Tomatoes Rating of the movie.
* Country where the movie was produced.
* Language of the movie.
* Plot of the movie.
* Actors in the movie.

![image](https://user-images.githubusercontent.com/46450079/55568449-58362400-56c5-11e9-9873-65aa95054b73.png)
video: https://drive.google.com/file/d/1OLYCfFdpwuwmroWFPvJ9DHDW8dgijKF2/view?usp=sharing

## 4. do-what-it-says
node liri.js do-what-it-says
LIRI Bot will run spotify-this-song for I Want it That Way. It reads the file random.txt and processes the commands in it (spotify-this-song, I Want it That Way) and runs it.

![image](https://user-images.githubusercontent.com/46450079/55568522-76038900-56c5-11e9-85a6-53ca846e9c4c.png)
video: https://drive.google.com/file/d/1dygplR9xd8omoFQX0Z-sPZchtq9f0ZBa/view?usp=sharing


## Built With:

### APIS:
* Spotify
* OMDB - For movie-this feature
* Bands In Town - for concert-this feature

### NPM Packages:

* Axios
* DotEnv
* Moment - Used for date formating
* Node Spotify API - For spotify-this-song feature

