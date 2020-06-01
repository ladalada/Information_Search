# Information_Search

### Tasks description  
https://docs.google.com/document/d/11cSEo51aR9A-Necomw2t6wt_v9-KvoUfEm-040plus0/edit

### Quality requirements
https://docs.google.com/document/d/1vPZ4E9NfMowo5TKF2N2g0Kqq_sX23rQbleLHDhcApYE/edit

### Dataset
https://www.brandwatch.com/blog/most-twitter-followers/

### Implementation
#### 1.1. Data Сollection 

Description of notebooks/1.1.DataСollection.ipynb:
* Collecting a list of users from a specified resource using the Beautiful Soup library. See data/usernames.txt
* Collecting a collection of documents from users' twitter using the twint library. See data/part_of_initial_data.csv

#### 1.2. Data Сleaning

Description of notebooks/1.2.DataСleaning.ipynb:
* Removing from the text tweets links to resources, images and videos
* Delete tweets from the text of all characters except letters
* Remove tweets from less than 50 characters

See data/part_of_cleared_data.csv

Description of 1.2.RemovingStopwords.ipynb:
* Remove stop words from tweet text
* Selection of document attributes

See data/part_of_data_without_stopwords.csv

#### 2. Exploratory Data Analysis 

Description of notebooks/2.ExploratoryDataAnalysis.ipynb:
* Number of tweets per users
* The most common words, mentions, hashtags on tweets
* The ratio of the number of tweets with and without mentions, hashtags, photos, video
* The distribution of the number of tweets by date and time of publication
* Distribution of the average number of replies, likes and retweets by the date and time of publication
