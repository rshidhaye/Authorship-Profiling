# Recommendation System:

A recommender system, or a recommendation system (sometimes replacing 'system' with a synonym such as platform or engine), is a subclass of information 
filtering system that seeks to predict the "rating" or "preference" a user would
give to an item.

First step is to load the necessary packages and libraries:

o implicit package needs to be installed.

Next is to load the training, testing and validation datasets in pandas and combining the training (the training set has data of users that have 
interacted with items) and validation (the validation set has data of users that have interacted and not interacted with items) sets so as to get 
the information whether the user has interacted with an item or not as validation set contains the combination of such data to train our models. 

Among the 3 models (ALS, BPR and LMF) and 1 ensembled model (ALS + LMF), ALS is the model which gave the best NDCG score for the data with confidence 
as 30, 8 latent factors, 0.1 regularization parameter with 1000 iterations while BPR gave the worst results.
