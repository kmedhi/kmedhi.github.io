### Collected twitter data using API method using Dr Ho's suggested docs

  * Using rtweet package, searched Twitter data by **username** `rdt <- rtweet::search_tweets(q = "narendramodi", n = 1000, lang = "en")` and **keyword** `rdt1 <- rtweet::search_tweets("indiachina", n = 1500)`
  * Created ts plot of the data by `mins` and `hours`
  * Created igraph of the data
 
 
 ## Analysis: 
  The data is from only one day, but we can make some analysis from it:
    * Twitter handles like PMOIndia, narendramodi, AmitShah, Rahulgandhi are in the dense part of the network, suggesting that their tweets ahve been retweeted the most.
    * Although a few influential names are showing on screen, influence is not of any significance as the data is taken only from one day.
