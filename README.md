# liri-node-app

Liri Bot application assignment
Liri Node App
This version application functions like SIRI except you type in your command instead
of speak them. Find a movie. Search song on spotify or let LIRI select one. All transactions
are documented in the log.txt file.

How to use commands:
Syntax for interface.
node liri.js command [arguments].

movie information for specified movie (when movie name is 1 word).
\$ node liri.js movie-this Blade.

movie information for specified movie (when movie name is 2 word).
\$ node liri.js movie-this shawshank redemption.

movie information for Mr. Nobody when no movie is specified.
\$ node liri.js movie-this.

Display top 10 songs on Spotify for the specified song name.
\$ node liri.js spotify-this-song What Ifs.

Display top 10 songs on Spotify from random.txt file, ex: I want it that way.
\$ node liri.js do-what-it-says.

Display song information for The Waiting by The Mowgli's when no song is specified.
\$ node liri.js spotify-this-song.

Display help commands to show you how to use the app.
node liri.js help.

======================================================

npm packages used:

dotenv.
request (omdb api).
node-spotify-api.
figlet.
fs.
