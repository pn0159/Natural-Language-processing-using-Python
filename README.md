# Text Analysis using Twitter Data

# About the project

Twitter has played a pivotal role in sharing of information and opinions on real time events. Sports events trend on all online social networks. One such popular event was Indian Premier League(IPL). IPL is the most popular cricket league in India with players from across the world. It is one of the most viewed and followed sports events in India. It is a showcase for Twenty-20 (T20) cricket, which is the shortest form of play in the game. Top Indian and international players participate in IPL, making it the world’s richest cricket tournament. My project goal is to extract insights from the text analysis(analyzing audience mentions in the form of tweets on match during the IPL season ) using Twitter data. In this work i have analyzed the online activity for the Indian Premier League 2020 match. For this, i have used online social media Twitter. Tweets posted by IPL match fans are collected using twitter API interface. I have collected the data with keyword/hashtag like #IPL2020 for collecting tweets related to match during IPL season. A series of IPL cricket matches between the teams Mumbai Indians (MI), Chennai Super Kings (CSK), Deccan Chargers (DC), Kings XI Punjab (KXIP), Kolkata Knight Riders (KKR),Sunrisers Hyderabad (SRH), Rajasthan Royals (RR) and Royal Challengers Bangalore (RCB) were chosen and tweets were collected from unique users on Twitter. The core of my work is to provide insights by analyzing audiences mentions for mega sport event in India (IPL) through analyzing the tweeter data. To evaluate this, i am using tweets data to find the team that has got more support/mentions , number of tweets per location, tweets sentiments , any milestones achieved by the team/player, top 10 topics audience were talking about. I have used Latent Dirichlet allocation(LDA), a topic modelling algorithm and k-means clustering to extract information on number of topics the tweets are majorly talking about, and to find any milestones achieved by particular team/players .Valence aware dictionary and sentiment reasoner (VADER) is used for tweets sentiments describing whether tweets are positive, neutral and negative. To visualize the topics i have used pyLDAvis. 

Furtherly I have also implemented 4 Classification algorithms namely Multinomial Naïve Bayes, Support Vector Machine (SVM) , Random forest and Gradient Boosting in order to predict and analyze the results of the sentiments by evaluating metrics like accuracy, f1-score, precision and recall score. I have used Word Cloud to visualize the most tweeted words by the IPL fans during the day tweets were extracted.

The business case is straightforward: Sport events like IPL create opportunities for marketers and media professionals to plan ad campaigns. Insights from this analysis could be an important factor to the advertisement agencies and to the brands who wish to sign-up certain players as ambassadors. The analysis for players across cities based on the target region furtherly helps for the brands to market their product efficiently in the market. The outcome of this project can be useful for every marketing and business professionals to plan ahead their business strategies during mega events like IPL. Therefore, with more of such studies on the IPL and on other such events we can possibly find trends and draw parallels to better understand user behavior in case of sport events.

At the conclusion of this project I have successfully developed data-driven insights and recommendations which can be utilized by the Media and Marketing professionals to find trends and draw parallels to better understand user behavior in case of significant sport events and to make decisions accordingly in marketing their business

# Research Questions

The main purpose of this study is to investigate sports-related information on Twitter. 

The questions/hypothesis that I would like to test using the data collected are:

1. Which team has got more mentions/support? 

2. Number of topics the tweets are majorly talking about

3. Any milestones achieved by particular team/players

4. Most tweeted words by the IPL fans.

5. Tweets per location

6. Variation in Sentiment of fans over hours on IPL

In contrast to traditional data sources like IPLT20, the study can furtherly be investigated whether Twitter may be utilized as a new data source to explore and draw insights on sports-related information.

# Tools Used

Python: Used Tweepy for gathering tweets, Corpus for data preprocessing, Word Cloud , pyLDAvis along with pie and bar graphs for Visualizing and NLTK-Vader for sentiment polarity calculation.

Google Colab: Implemented analysis in python using Google Colab

# Summary

Through this analysis, it is evident that Mumbai Indians team has got more mentions, and users from India especially from states New Delhi, Chennai and Mumbai are more tweeting, also #IPL2020 and #IPLfinal being top #tags during season. I observed the number of positive tweets far outweigh the number of negative tweets, I generated topics using the above-mentioned techniques and their summarization were made along with predictions of sentiments, where SVM model showed accuracy of 78%. From this analysis I can conclude that attitude of people who keep tweets has been changed during the season and most of the people’s attitude towards the IPL2020 match is positive
