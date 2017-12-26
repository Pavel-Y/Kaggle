## Catch Me If You Can

[Competition link](https://www.kaggle.com/c/catch-me-if-you-can-intruder-detection-through-webpage-session-tracking2/leaderboard)

### Description
Data contains information about user's internet session. Session duration is 30 minutes or 10 sites.
If a user has visited less than ten sites in 30 minutes the rest of session is left empty.
The problem of the competition is that we need identified one specific user and we have less that one percent of her session, 
so this task looks more like anomaly or chunk identification. 

### Target
Find one specific user
 
### Metric
 Roc-auc curve
 
### Models
 * TfidfVectorizer    - for data preprocessing 
 * LogisticRegression - for creating submissions
  
### Result
 * Public leaderboard  - 0.94699 and 58 place out of 289
 * Private leaderboard - is unknown for now
