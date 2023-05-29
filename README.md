# Named-Entity-Recognition
In this task we got data with sentencew and for each sentence we need to predicy for each word if it is Name-Entity or not.
We used various models:
1. The first model was Knn with embedding of World2Vec concatenate to glove.
2. The second model was feet-forward neural network with embedding of World2Vec concatenate to glove.
3. The third model was Bi-directional LSTM with embedding of World2Vec concatenate to glove.

The evaluation function of the model was F1 because the data was imbalance.
