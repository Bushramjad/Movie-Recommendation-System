# Movie Recommendation System
Matrix factorization is based on the assumption that

- Each user can be described by k attributes or features. For example, feature 1 could be a number indicating how much each user enjoys sci-fi movies.
- Each item (movie) can be described by a set of k attributes or features. To correspond with the preceding example, feature 1 for the film could be a number indicating how close the film is to pure sci-fi.
- If we multiply each feature of the user by the corresponding feature of the movie and add everything up, we can get a good estimate of the rating the user would give that movie.

Gradient Descent, Stochastic Gradient Descent, and Alternating Least Squares are well-known algorithms used in the matrix factorization solutions to minimize the loss
