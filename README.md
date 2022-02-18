# Network Twitter Mentions

In this repository is built a network of mentions and a study of the network using the names of users and mentions in the tweets of these users. For this, the Python programming language and packages were used to handle the data and generate graphics. For the construction of the network, the Twitter API was used to search for tweets with the hashtag #covid19 in Portuguese. The mention network is built with nodes representing users and an edge is added when the tweet creator mentions someone in that tweet, the edge is directed from the tweet creator to the mentioned user.
  
## Network

<center><img width="600" src="https://github.com/matheusriv/network_twitter_mentions/blob/main/image/grafo.png"></center>
<center>
  
To explore the graph visit this [link](https://matheusriv.github.io/network_twitter_mentions/network/).
 
The page is a visualization of the network created using Gephi, an open source software package for analyzing networks and graphs. The network was exported with Gephi's Sigma export plugin.
