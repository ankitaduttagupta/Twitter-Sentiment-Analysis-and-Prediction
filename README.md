## Twitter Sentiment Analysis and Prediction of SXSW 2011, Austin
**Given : evaluated tweets about multiple brands

Dataset has **7273** tweets with the sentiment label
3 columns: 

Tweet_id : unique id for tweets

Tweet : tweet about the brand / product

Sentiment : 0 : negative, 1 : neutral,  2 : positive,  3 : can't tell

**Metric for evaluation= weighted F1 score**

**Supervised Multi-classification Problem**

**Final model used - RandomisedSearchCV on linearSVC with weighted f1 score of 0.656**
 
