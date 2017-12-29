# Data Science assignment data
# {Fixing Mentions}
Trump's twitter data collected using python-twitter. Note that much of the data has not been downloaded in the case of followers and tweets. There is also some missing data from Favorites.
## Tweets
Each file is a Trump tweet or retweet. The data starts from 2016-10-05 and ends at 2017-12-15
## Followers
Each file represents a cursor call to getFollowers and contains a list of followers. Each file's extension is .txt, should technically be .json
## Follows
1 file representing the 0 cursor call to getFriends and contains a list of follows. The file's extension is .txt, should technically be .json
## Favorites
Favorited by Trump, 19 tweets starting from 2013-03-02 to 2017-11-03
## User
Contains a json file representing Trump's twitter user.
## Mentions
Contains mentions of #realDonaldTrump and @realDonaldTrump. Collected using the getSearch() function in python-twitter while using max_id's.
