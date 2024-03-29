# Working-with-Databases-JPA-Challenge

Create a new Entity, named Song, for the music.songs table.  
Edit the Album Entity, adding a list of your Song entity as a field, and include this list, in the toString output.
Edit the Main class, retrieving a single artist by id, confirming songs are now part of the artist data, that's retrieved.
Create a SongQuery class that's similar to the MainQuery class, from the previous video.  It should include a method to query the music data, returning any artist, with an album with a song that contains matching text of your choice.  For example, the words "Storm", "Dead", or "Soul" are in a variety of song titles, in albums for different artists.  
Print the artist name, album name and the matching song title, that contained the text.


Include fields that line up with the columns in the songs table. 
Be sure to annotate the class and each field correctly. 
Create at least one constructor.
Generate some getters for fields your application might need access to.
Override or generate a toString method, that prints the fields of interest.


Add a list of songs to the Album Entity.
Use annotations to set up proper entity relationships for the new field.
Change the toString method on albums, to first sort songs by track number, then output each song on its own line.

To test your entity, I want you to edit the Main class and main method.
Importantly, Make sure you test a different artist id, than 202, as it's set up now, because this artist's only album has no songs. 
Make sure you remove or comment out any code, that inserts, or adds data to the entities.
Confirm you're now retrieving songs as well as the other artist data.



To test your entity, I want you to edit the Main class and main method.
Importantly, Make sure you test a different artist id, than 202, as it's set up now, because this artist's only album has no songs. 
Make sure you remove or comment out any code, that inserts, or adds data to the entities.
Confirm you're now retrieving songs as well as the other artist data.



