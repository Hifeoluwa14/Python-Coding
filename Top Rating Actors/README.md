# Top Rating Actors
## Problem Statement 
Find the top actors based on their average movie rating within the genre they appear in most frequently. 
• For each actor, determine their most frequent genre (i.e., the one they’ve appeared in the most). 
• If there is a tie in genre count, select the genre where the actor has the highest average rating. 
• If there is still a tie in both count and rating, include all tied genres for that actor.

Rank the resulting actor + genre pairs by their average rating in descending order. 
• Return all actor + genre pairs that fall within the top 3 ranks (not rows), including ties. 
• Do not skip ranks — for example, if multiple actors are tied at rank 1, the next rank is 2.

The data is provided in a dataframe named top_actors_rating.csv and it contains the following columns:

• actor - name of the actor;

• genre - genre of the movie;

• movie-rating - rating of the actor in the movie;

• movie_title - name of movie;

• release_date - movie release date;

• production_company - company that poduced the movie.

## Solution
The Solution to the problem is available in the attached Jupyter notebook. It well documented and easy to follow
