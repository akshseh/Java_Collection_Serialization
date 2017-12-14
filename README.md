# Advanced_programming Assignment 

This assignment is based on the java collections, serialization and will also use previously studied concepts in java.
Create a media system Library:

- Which can have both movies and songs.
- A  Media  class which implements Comparable interface should have properties like title
(unique), artist (for simplicity a single artist), year, size, rating (1.5), duration, genre.
- In addition,
  - a  Movie  should have a director, producer, certification.
  - a  Song  should have movie (independent / movie name) label.
- You should have a main class called M  ediaSystem  with attributes as list of movies,
songs, number of songs/movies and following functionalities:
  - Serialize and deserialize MediaSystem class.
  - View a list of all the songs/movies in the library and see information about each song/movie.
  - View a list of top “k” songs/movies by their rating.
  - Search and display songs based on genre.
  - Search and display movies based on director.
  - Edit the rating of a song/movie.
  - Display the count of number of songs/movies.
  - Search and display all the songs of a given movie.
- **Bonus:** Create your own stream class to encrypt and decrypt the MediaSystem. You should be able to use this stream as decorator in conjunction with Java SDK streams. The focus of the question is not how you encrypt/decrypt but the decorator pattern. You may use some naive encryption as translating characters.

## Input:
1. You will be given 2 database files (comma separated values), one for songs and other for movies.

Song.txt  `<Song>`,`<Movie Name>`,`<Artist>`,`<Year of Release>`,`<Genre>`,`<Size>`,`<Rating>`,`<Duration>`

Movie.txt `<Movie>`,`<Artist>`,`<Year of Release>`,`<Genre>`,`<Size>`,`<Rating>`,`<Duration>`,`<Director>`,`<Producer>`,`<Certification>`

