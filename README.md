# liri-node-app

<<<<<<< HEAD
=======
LIRI is a Language Interpretation and Recognition Interface.

## Overview

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI is a command line node app that takes in parameters and gives data in return.

This is a command line app that queries the spotify API, OMDB API and Bands in Town API and neatly returns to users information about their requested film, band, or movie.

## What Each Command Does
LIRI searches **Bands in Town** for concerts, **Spotify** for songs, and **OMDB** for movies


## 1.concert-this
 node liri.js concert-this <artist/band name here>
 This will search the Bands in Town Artist Events API for an for an artist and render the following information about each event to the terminal:
* Name of the venue
* Venue location
* Date of the Event (use moment to format this as "MM/DD/YYYY")

## 2.spotify-this-song
This will show the following information about the song in your terminal/bash window:

* Artist(s)
* The song's name
* A preview link of the song from Spotify
* The album that the song is from

![GitHub Logo](spotify-this.png)
Format: ![Alt Text](url)
(spotify-this.png)
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


## 4. do-what-it-says
node liri.js do-what-it-says
LIRI Bot will run spotify-this-song for I Want it That Way. It reads the file random.txt and processes the commands in it (spotify-this-song, I Want it That Way) and runs it.


## command not found
If the command is not one of the ones specified above, the program will print a menu like so:

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
>>>>>>> 172f09f060f3da92d35940a0995e6f87c140e67e
