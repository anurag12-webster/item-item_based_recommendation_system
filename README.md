## item-item_based_recommendation_system

The item-item based system is helpful to recommend items to users based on similarities between items. 
It uses  the idea that users who have shown interest in one item are likely to be interested in similar items.

For example we can see whenever we buy a smartphone we get the mobile cover or charging brick suggested.
it's a perfect example of item-item based recommendation.

Imagine you have a list of movies and ratings given by different users. This program takes that data and uses it to suggest similar movies to the one you choose.
The program reads information from two files. One file contains user ratings for different movies, while the other file contains additional details about each movie, such as its title and genre.
after reading the data, the program organizes it into a table-like structure & it arranges the data in a way that each
row represents a movie, each column represents a user, and the entries are the ratings given by users to those movies. If a user hasn't rated a particular movie, the entry is filled with zero.

the similarity for chosen movies with the other is calculated based on two methods
by [comparing the movie rating] or by [comparing the movie metadata]
hen you select a movie from the provided list, the program uses the similarity information to suggest movies that are similar to your chosen one. If 
the selected movie has received enough ratings from users, it will use the ratings-based similarity. Otherwise, it will use the metadata-based similarity to make recommendation.

and for the interface i have used the Streamlit Library.
