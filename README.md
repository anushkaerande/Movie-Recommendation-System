# Movie-Recommendation-System
To build a Movie recommendation Engine using Cosine similarity and CountVectorizer.
# What it does
It recommends movie according to input movie name given. Attributes taken into account while recommending are director name, movie name, actors, genre.
# How it does
Movie recommendation engine recommends movies based on the user input.Output is
produced as top 10 movies similar to movie, which user has given as input. Cosine
similarity is used to find similarity between different movies.Unlike k-nearest neighbor
Euclidean distance doesn’t matter.
This is a dynamic way of finding the similarity that measures the cosine angle
between two vectors in a multi-dimensional space. In this way, the size of the
documents does not matter. The documents could be far apart by the Euclidean
distance but their cosine angle can be similar.Model is developed using skit-learn
library in python. As for cosine similarity we need to find angles thus we use a count
vectorizer which converts data into vector representation.
# team members
Saniya Damle, Anushka Erande
