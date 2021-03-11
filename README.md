## The right opinion? Anti-vax conspiracies on Reddit
Topic analysis and clustering of vaccine-related comments on the subreddit r/conspiracy.
Based on the analysis in *Klein C, Clutton P and Polito V (2018) Topic Modeling Reveals Distinct Interests within an Online Conspiracy Forum. Front. Psychol. 9:189*
## Method
I used NMF for getting topics, and then k-means clustering on document-topic loadings.
## Hypothesis
Content of anti-vax conspiracies shifted over time.
## Result
Gathered 8 anti-vax themes. Share of comments discussing each theme did not change much across 2020. Hypothesis doesn't hold.
![cluster_share_week](https://github.com/tripartitestruggle/reddit-anti-vax/blob/main/output/images/cluster_share_week.gif?raw=true)
![cluster_descriptors](https://github.com/tripartitestruggle/reddit-anti-vax/blob/main/output/images/table1.png?raw=true)
![topic_cluster](https://github.com/tripartitestruggle/reddit-anti-vax/blob/main/output/images/topic_cluster.png?raw=true)