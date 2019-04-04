# liri-node-app

This is a command line app that queries the spotify API, OMDB API and Bands in Town API and neatly returns to users information about their requested film, band, or movie.

## Commands
List of the commands that are used for this app. 

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
*node.js - Javascript runtime environment
*Moment - Used for date formating
*Node Spotify API - For spotify-this-song feature
*Bands in Town Events API - for concert-this feature
*OMDB API - For movie-this feature
