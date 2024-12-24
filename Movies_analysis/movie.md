## Content

There are 6820 movies in the dataset (220 movies per year, 1986-2016). Each movie has the following attributes:

- budget: the budget of a movie. Some movies don't have this, so it appears as 0


+ Title: The title of the movie or TV series.

+ Released_Year: The year the movie or TV series was released.

+ Runtime: The total runtime of the movie or TV series, usually given in minutes.

+ Genre: The genre or categories the movie or TV series falls into, such as Action, Comedy, Drama, etc.

+ Rating: The rating of the movie or TV series on IMDb, typically on a scale from 1 to 10.

+ Meta_score: The Metascore from Metacritic, which aggregates reviews and gives a score from 0 to 100.

+ Director: The director of the movie or TV series.

+ Votes: The number of votes the movie or TV series has received on

+ Categorical Variables: Series_Title, Genre, Director

+ Revenue (Millions) :

+ Rank :

+ Description : 

+ Actors : main actor/actress

+ Years : year of release

+ Numerical Variable: Released_Year, Runtime, IMDB_Rating, Meta_score, No_of_Votes

## Analysis Tasks to be performed:

* Explore the datasets using visual representations (graphs or tables), also include your comments on the following:
   
  1. User rating of the movie “Toy Story”
  2. Top 25 movies by viewership rating
  3. Find the ratings for all the movies reviewed by for a particular user of user id = 2696

* Feature Engineering:
Use column genres:
  1. Find out all the unique genres (Hint: split the data in column genre making a list and then
process the data to find out only the unique categories of genres)
  2. Create a separate column for each genre category with a one-hot encoding ( 1 and 0) whether or not the movie belongs to that genre.
  3. Determine the features affecting the ratings of any particular movie.
  4. Develop an appropriate model to predict the movie ratings

  ## Dataset Description :
These files contain 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040
MovieLens users who joined MovieLens in 2000.

* Genres are pipe-separated and are selected from the following genres:
  1. Action
  2. Adventure
  3. Animation
  4. Children's
  5. Comedy
  6. Crime
  7. Documentary
  8. Drama
  9. Fantasy
  10. Film-Noir
  11. Horror
  12. Musical
  13. Mystery
  14. Romance
  15. Sci-Fi
  16. Thriller
  17. War
  18. Western


## Data Analysis 

 * ***Top 5 Movies and it's directors***
```
Title	     Director
0	     Guardians of the Galaxy James Gunn
1	     Prometheus	Ridley Scott
2	    Split	M. Night Shyamalan
3	    Sing	Christophe Lourdelet
4	    Suicide Squad	David Ayer
5	   The Great Wall	Yimou Zhang
```

* ***Mean Rating of Director***
```
Director
Aamir Khan             8.50
Abdellatif Kechiche    7.80
Adam Leon              6.50
Adam McKay             7.00
Adam Shankman          6.30
                       ... 
Xavier Dolan           7.55
Yimou Zhang            6.10
Yorgos Lanthimos       7.20
Zack Snyder            7.04
Zackary Adler          5.10
```

### Unique Genre

```
Rank	Title	Genre	Description	Director	Actors	Year	Runtime (Minutes)	Rating	Votes	Revenue (Millions)	Metascore
7	8	Mindhorn	Comedy	A has-been actor best known for playing the ti...	Sean Foley	Essie Davis, Andrea Riseborough, Julian Barrat...	2016	89	6.4	2490	NaN	71.0
25	26	Paris pieds nus	Comedy	Fiona visits Paris for the first time to assis...	Dominique Abel	Fiona Gordon, Dominique Abel,Emmanuelle Riva, ...	2016	83	6.8	222	NaN	NaN

```