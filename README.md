# tj_predictor // Tommy John Predictor

This project was an attempt to predict whether or not an MLB pitcher would succumb to Tommy John surgery during the current season. This could be helpful when signing a player to a league as a free agent, or avoiding said player during a draft.

I examined every available stat on fangraphs (~160 features) and used data from 2009 to 2016. 

Models I tried: 
  * linear regression 
  * decision tree with random force classifier 
  * logistic regression
  * KNN

I was unable to accurately predict the likelihood of surgery - I couldn't get an ROC score over 0.51 (to be reliable, it should be over 0.8). I came to the conclusion that I didn't use enough data.

In the future, I would delve into Statcast data and create a quantitative value for pitcher usage (stress innings, bullpen time) to diverisfy the dataset. 
