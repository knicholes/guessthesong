#GuessTheSong
is a project to learn [angularjs](http://www.angularjs.org/), [socketio](http://socket.io/), and [Node.js](http://nodejs.org/).
This app will allow users to hop into a "chatroom" and listen, simultaneously, with a group of friends to the same song.  Each person may guess which song they're hearing.

The initial plan is to use grooveshark's [tinysong API](http://developers.grooveshark.com/tuts/tinysong) (if possible-- research necessary) to retrieve songs from a playlist.  This playlist will initially be pre-defined, but eventually we should add the ability to add your own playlists that others can play with.

Things to discuss:

[ ] Can anyone create/join a playroom (chatroom/playlist)

[ ] Can users build their own playlists?

[ ] Should a song play until it's complete or until everyone has guessed?

[ ] How accurate does an answer have to be?  (Artist name only?  Song name + artist name? Just song name?  80% of name?)

[ ] How long does a game last?  When is a winner determined?

[ ] Is there going to be a high-scores list?  If so, is it per playlist?  Per group of friends?  Per day?  Per user?

[ ] Can a playlist be modified in-game?

[ ] When is the correct answer revealed?

[ ] How will the user input an answer?  Text?  Multiple choice?

[ ] How many guesses does the user get?

[ ] Will there be different difficulty levels?  If so, by playlist (more obscure songs?), by time given to name the song, powerups to eliminate options or give hints?

- - - 

###Setup
install [Node.js](http://nodejs.org/), [Git](http://git-scm.com/book/en/Getting-Started-Installing-Git) and optionally, [Ruby](https://www.ruby-lang.org/en/downloads/)

npm install -g yo
bower install
###To test run
grunt test
###To preview app
grunt serve
###To build app for deployment
grunt


