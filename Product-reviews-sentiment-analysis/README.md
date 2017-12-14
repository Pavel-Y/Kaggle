## Product review sentiment analysis

[Competition link](https://www.kaggle.com/c/product-reviews-sentiment-analysis/leaderboard)

### Description
Only test dataset is given. 
So it needs to be done:
 * Parse train dataset somewhere on the internet
 * Mark raw data
 * Train model and send prediction
 
As a source of train data I've decided to use market.yandex.ru, as a site with good structure and huge amount of reviews. 
What makes it easy to parse all necessary data. But due to organizer of the competition is Yandex as well I think that there are some 
intersections in train and test data, which has brought such good result.

### Target
 Classify user review on two classes (positive and negative)
 
### Metric
 Accuracy
 
### Models
 * RussianStemmer   - as data preparation
 * CountVectorizer  - as data vectorization
 * TfidfTransformer - as transformation of vectors
 * RidgeClassifier  - as classifier
  
### Result
 * Public leaderboard  - 100% and 11 place :)
 * Private leaderboard - is unknown for now
