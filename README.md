#  Investigating 10,000 movies collected from The Movie Database (TMDb)

## Overview

Exploring The Movie Database (TMDb) to answer chosen questions about movies and genres:
- How did several genres fare through the years?
- Does a high budget guarantee a high revenue? and which movie has the highest budget to revenue ratio?
- Does a movie runtime affect the revenue? and is the average movie runtime increasing over the years?
- Who is the most accomplished director in terms of total revenues and total average scores of his movies?
- Who are the most productive directors in terms of number of movies made?

## Tools

- Python (numpy, pandas, matplotlib, seaborn)

## Findings

- **How did several genres fare through the years?** : we selected these genres to investigate ( Action, Comedy, Animation, Horror, Documentary, and Western) of which Comedy genre showed the highest rate of increase and the remaining genres showed also an increase in number of the years except for the western genre.
- **Does a high budget guarantee a high revenue? and which movie has the highest budget to revenue ratio?** : we found that there is a relationship between movie budget and its revenue but it's not that strong, this was indicated by the correlation coefficient which showed a positive but moderate relationship. high budget does not guarantee a high revenue but it helps. The movie with the highest budget to revenue was The Karate Kid, Part II
- **Does a movie runtime affect the revenue? and is the average movie runtime increasing over the years?** : We found that there is a weak positive relationship between the movie runtime and its revenue, indicated by the correlation coefficient. movie runtime does not have a strong effect on the revenues of the movie. also, we found that the average movie runtime tend to decrese over the years.
- **Who is the most accomplished director in terms of total revenues and total average scores of his movies?** : We found that the most accomplished director in terms of total revenues of his movies was Steven Spielberg, and the most accomplished director in terms of the average scores of his movies was Mark Cousins.
- **Who are the most productive directors in terms of number of movies made?** : We found that the top 5 most productive directors are Woody Allen at the top with 45 movies followed by Clint Eastwood then we have a draw between Martin Scorsese and Steven Spielberg then at number 5 we have Ridley Scott with 23 movies.
