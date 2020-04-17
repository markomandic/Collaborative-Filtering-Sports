# Collaborative-Filtering-Sports

Collaborative Filtering is traditionally used for user recomendation systems. This projects explores the posibilities for using this method for head to head matchups in different sports. There are several challenges in doing so. 
1) What constitutes a valid data point? Is the matchup between two players determined by their overall head to head record, a recent record and if so what's the minimum amount of matchups required before the record is meaningful?
2) How will the data sparsity affect the results in different sports?
3) Are sport outcomes by definition too random to make predictions based on matchups? Ie. is each player so different from all the others that their embeddings don't capture enough meaning not to be random?

This projects explores these questions for baseball, tennis, and snooker datasets.
