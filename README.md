# Recommendation System

This is a repository to create Recommendation Systems using various 
Machine Learning algorithms. 

### PROJECT: Basic Recommendation System Using Neural Network </br> 

Dataset: [Book Crossing Dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/) <br/>
Built for: Top 50 users <br/>
Input features: User IDs, Book ISBNs <br/>
Output target: Ratings (not-rated books labeled as 0 and 
rated books labeled as 1) <br/>
Training set: 199 books rated and 400 books not rated by an user  <br/>
Test set: 1 book rated and 600 books not rated by an user.  <br/>

Algorithm: Fully Connected Neural Network <br/>
Loss function: Cross Entropy Loss <br/>
Evaluation results: Hit rate 0.58 and Number of hits 29 <br/>
Findings: The trained model seems to be recommending books that are published 
in the same decade for a user. <br/>
Conclusions: With a more imbalanced training set containing far more 
not-rated items than the rated items the model training is more difficult 
and results in a lower hit rate for a longer recommendation list. <br/>


