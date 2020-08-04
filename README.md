# udacity-capstone


communicates the libraries used, the motivation for the project, the files in the repository with a small description of each, a summary of the results of the analysis, and necessary acknowledgements

My capstone project for Udacity's Data Scientist  Nanodegree

Topic: Clustering analysis for time-series sales data

## Dataset
The dataset is an anonymised and transformed version of a commercial sensitive sales quantity dataset, split on retailer and item

Note: The anonymised dataset is contained in this repo

## Requirements , libraries: 

* pandas 
* numpy 
* random 
* itertools
* matplotlib
* seaborn 
* sklearn
* scipy

## Motivation
My motivation initially was to see if I could answer a potentially popular business question of how can we group our customers by using the data we have on their purchasing patterns over time. It was a particularly interesting subject for me as it onvolved clustering time series which I have never done before.
## Repo summary
The repo contains:
* *data file* - unstacked_udacity.csv
* a helper file - *helper.py* that contains self written functions
* The notebook with the analysis 
## Summary
* I have discovered that if we use the item_retailer combination, this proves to be granular enough to produce rather meaninful looking clusters
* A plesant surprise was to discover the effect of covid19 on the sales and how clustering was able to capture different behaviours across retailers in that time of when pandemic broke out.
* As a follow for the futureup, I'd like to mention that analysis like this could help with predictive modelling  . For example: instead of training a model on the entire dataset, it may make sense to train one model per cluster, as the underlying structure of the series' are similar within a cluster. 
* I would also like to mention that next time I would also try different clustering techniques and try obtaining longer time series. 
* Perhaps it could also be worth trying to take daily series in rather thanb goign straight for the weekly.
* It could also be a good idea to cluster on a more granular level such as store level as an example
## Acknowledgements
I would like to thank everyone involved , Udacity for providing the opportunity to work on this and my other half for the moral support :)
