# Review Article "Analysis and mining of an election-based network using large-scale twitter data: a retrospective study"

## Source:
https://link.springer.com/content/pdf/10.1007/s13278-023-01081-0.pdf

## Overview

### Methodology
The article employs social network analysis to study Twitter data related to state assembly elections. The authors create a 'reply-to' network based on tweets and replies. They categorize network actors into three groups: Politicians, Media, and Users. The analysis is conducted for the 1st, 4th, and 6th weeks of their study period, covering initial, medial, and final periods of the elections.

### Metrics Used
- **Cluster Dominance**: Measures the number of tweets made in favor of each of the three political clusters. This is calculated as a weekly relative percentage.
- **Centrality Measures**: Degree Centrality, Betweenness Centrality, Page Rank, Eigenvector Centrality, Authority, and Hub Centrality are used to identify key roles played by actors in the network.

### Observations
- **Week 1**: Cluster 1 dominates in terms of hashtag usage. The network is less connected with fewer than one edge per node on average.
- **Week 4**: Cluster 2 gains dominance. The network is better connected, and multiple actors have high degrees of centrality.
- **Week 6**: The network is more well-formed than in previous weeks, with Cluster 2 maintaining its dominance.

The authors validate their findings by comparing them with opinion and exit polls. They conclude that their approach aligns well with the ground reality of the election outcome.


## Cluster Meaning

### Meaning of Each Cluster

The article employs social network analysis to study Twitter data related to state assembly elections. The authors categorize hashtags into three pre-determined clusters, each representing a specific political alignment or ideology. Here are the meanings of each cluster:

*   **Cluster 1**: This cluster is associated with hashtags like `bengalwithbjp`, `tmchataobanglabachao`, and `banglarmanushbjpersathe`. These hashtags suggest that this cluster is in favor of the BJP (Bharatiya Janata Party).
    
*   **Cluster 2**: Hashtags such as `banglargorbomamata`, `bengalwithdidi`, and `votefortmc` are part of this cluster. These hashtags indicate that this cluster supports the TMC (Trinamool Congress) and its leader Mamata Banerjee.
    
*   **Cluster 3**: This cluster includes hashtags like `bengalneedsleft`, `savebengalfromtmcbjp`, and `vote4sanjuktamorcha`. These hashtags imply that this cluster is aligned with left-wing parties or alliances.
    

The clusters are used to segregate hashtags and, by extension, the tweets and nodes (users) that use them. This helps in identifying the particular political cluster favored by each node in the network.



## Tweet Reviwed?
how many politiciaon, influencer and normal user is in this review?

### Number of Tweets Reviewed

The article initially gathered a total of 29,462 tweets for the study duration, which spanned over 6 weeks. After removing duplicates, the tweet corpus was reduced to contain 26,180 tweets.

### Distribution Among User Categories

The actors in the network were categorized into three groups:

*   Politicians
*   Media (which can be considered as influencers for the context of this study)
*   Users

The article does not provide specific numerical data on the distribution of these categories.




## Summerize Conclusion

### Conclusion Summary

The article concludes that the proposed method of cluster dominance based on hashtag extraction from tweets is effective in forecasting election outcomes. The authors observed that Cluster 2 established a clear majority in terms of Twitter activity related to 'bengal election', followed closely by Cluster 1. Cluster 3 had the lowest dominance and failed to secure any seats in the State Assembly. These observations were in line with the actual election outcomes. The method was also robust against challenges like auto-generated tweets or tweets by bots, which could introduce bias.

The authors claim that their approach is capable of capturing minute changes in ground reality, as evidenced by the dip in the online dominance of Cluster 1 during the 6th week of the study, which was also reflected in the actual poll results.
