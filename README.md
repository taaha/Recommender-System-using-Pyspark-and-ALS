# Otto Recommender System using Pyspark and ALS

This projects was done to practice pyspark and ALS concepts

This recommender system dataset belongs to german online retailer 'Otto'  and was taken from the following kaggle competition

https://www.kaggle.com/competitions/otto-recommender-system

This datset has 12 million users, 2 million items and 200 million events (clicks,carts and orders)

Following tasks were performed

1. Converting data from original jsonl format to parquets

2. Training ALS model on the parquets. To save compute, rank and iteration is kept small at the cost of accuracy

3. Computing top 20 recommendations for items in test data
