# Sentiment_analysis_bitcoin
This was a project I worked on in May 2018 to investigate the question, "Can Twitter sentiment be used to predict Bitcoin prices?"

My methodology was as follows:
1. EDA of tweets
2. ETL: used TextBlob to assign sentiment to the tweets; merged Bitcoin and tweet data
3. Analysis: undertook sentiment analysis; carried out correlation analysis
3. Modelling: preprocessing involved transforming BTC price into binary outcome; tried different machine learning models 

Results: Logistic regression model achieve 68% accuracy (random accuracy=59%) using the sentiment of bitcoin tweets to predict bitcoin prices (y= BTC, x= Sentiment)

Libraries used: numpy, pandas, seaborn, matplotlib, TextBlob, WordCloud, sklearn
