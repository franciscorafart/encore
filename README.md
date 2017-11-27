Live music playlist voting system app
With this app music fans can create vote for the playlist an artist will perform at a concert. The artist offers a list of songs they can perform and
a date for the end of the survey. The fans vote for the songs they like. When the time of the survey is done, the tracks at the bottom of the list
get erased and only the most voted reaimn in the playlist.

Link: http://franciscorafart.com/links/encore/index.html

How It's Made:

Tech used: HTML, CSS, JavaScript, Firebase
The app works by loading a database from Firebase. Each element of the database (a song) is a added to a table. Each element in the table has
different buttons that allow the user to vote. There's also a 'backend' section where we can create entries in the database. Eventually these
two functionalities will be separated.

Optimizations
This is work in progress. Eventually the user will be able to log in and they will have only a few votes. Also, the app that the artist uses
will be separated.

Lessons Learned:

I learned how to optimally load tables from Firebase and sort them according to arbitrary criteria. Also, when adding listeners to the 
different dynamically generated UI elements I learnt the difference between 'var' and 'let' variables in Javascript, and the implications 
that their scopes have. I also learned how to handle the SetInterval method, and how to stop it when the task required is done.
