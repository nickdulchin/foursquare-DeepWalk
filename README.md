# Foursquare_Recommendations_from_DeepWalk

I used random walks in a network (DeepWalk algorithm) to create a Foursquare recommendation system that recommends venues to users based on their check-ins. In order to test my model against a baseline, I also built three other models. The first is simply a model that recommends randomly and the other two use matrix factorization (with two different loss functions). Matrix factorization is one of the most standard approaches in the field.

*The embeddings file used in the notebook was created using the CLI made by the DeepWalk authors (https://github.com/phanein/deepwalk)
