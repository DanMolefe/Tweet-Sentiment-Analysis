# Tweet-Sentiment-Analysis

Twitter sentiment analysis is the process of determining the emotional tone or opinion expressed in tweets about a particular topic, brand, event, or product. This analysis can help businesses, researchers, and analysts understand public sentiment, monitor brand health, or gauge reactions to specific events. In this notebook, I used sentiment analysis for tweets (data taken from Twitter_training.csv located here https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis) related to these products: 
Borderlands, CallOfDutyBlackopsColdWar, Amazon,Overwatch, Dota2,PlayStation5(PS5), WorldOfCraft, CS-GO,Google, ApexLegends, LeagueOfLegends, Fortnite, Microsoft, Hearthstone, PlayerUnknownsBattlegrounds(PUBG), Verizon, HomeDepot, FIFA, CallOfDuty, TomClancysRainbowSix, Facebook, GrandTheftAuto(GTA), MaddenNFL, johnson&johnson, Cyberpunk2077, and TomClancysGhostRecon to extract product related sentiment.

The code for doing this analysis works as follows:

**Data**

* Read data with tweets. 

**Preprocessing** 

* Cleaned and preprocessed data. 

* Removed stop words, links, special characters, and irrelevant content. 

* Tokenized tweets - text was broken down into individual words or phrases.


**Sentiment Classification**

* Tweets were categorized using their emotional tone. 

* The primary classifications are:

    - Positive Sentiment - tweets that express favorable opinions or emotions.

    - Negative Sentiment - tweets that express unfavorable opinions or emotions.

    - Neutral Sentiment - tweets that are neutral or contain no strong opinion.

**Notes** 

* While Twitter sentiment analysis provides valuable insights, it’s important to note that it’s not always 100% accurate, due to challenges like sarcasm, context, or ambiguous language in tweets.

**List of variables**  

* id	
* product	
* sentiment	
* tweet_text
