# movie_reviews_sentiment_analysis_with_CNN
This is repository for Movie Review sentiment analysis with CNN and word embedding model.
1. About Dataset
  
  i. MovieReview- Train Dataset with review and sentiment column. 
     Total Reviews= 1000, Positive=500, Negative=500
  
  ii. movie_review_test - Test Dataset with review and sentiment column.
     Total Reviews= 500, Positive=250, Negative =250
     
2. Word Embedding: A word embedding is a way of representing text where each word in the vocabulary is represented by a real valued vector in a high-dimensional space. The vectors are learned in such a way that words that have similar meanings will have similar representation in the vector space (close in the vector space).

  Word Embedding Algorithms
  
  i. Embedding Layer: An embedding layer, for lack of a better name, is a word embedding that is learned jointly with a neural network model on a specific natural language processing task, such as language modeling or document classification.
  
  ii. Word2Vec: Word2Vec is a statistical method for efficiently learning a standalone word embedding from a text corpus. it is pre-trained word embedding, we can 
     use it as transfer learning.
     
 **I used Keras Embedding layer.  
 
3. Sequential Model: i used Sequential model, it allows us to build a model layer by layer. we used the add() function to add layers like Dense, Flatten, Embedding, and convolutional layers to model.
