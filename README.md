# Naive_bayes-on-amazon-fine-food-reviews
Given a review, Using Naive bayes model determine whether the review is positive (rating of 4 or 5) or negative (rating of 1 or 2). [Q] How to determine if a review is positive or negative? 
[Ans] We could use Score/Rating. A rating of 4 or 5 can be considered as a positive review. A rating of 1 or 2 can be considered as negative one. A review of rating 3 is considered nuetral and such reviews are ignored from our analysis. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.

.ipynb file consist also of feature importance and scoring in the form of accuracy,f1 score,precision score and recall score  

Models used: Sklearn Naive bayes classifer - ComplementNB, Vectorizers used : Bow (sklearn-CountVectorizer),Tfidf(sklearn-TfidfVectorizer)

Results obtained:

| Vectorizer |    Model     | hyperparameter | Accuracy | precision score | f1 score | recall score |
+------------+--------------+----------------+----------+-----------------+----------+--------------+
|    Bow     | ComplementNB |     3.2601     | 89.4821  |      0.9347     |  0.9369  |    0.9391    |
|   Tfidf    | ComplementNB |     0.7901     | 89.0299  |      0.925      |  0.9347  |    0.9447    |
+------------+--------------+----------------+----------+-----------------+----------+--------------+

