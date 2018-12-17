# Clustering-Project-FIFA

In this excel file I did a clustering project in Fifa

1. I cleaned the data by using filter method to get only 4 clusters: GK, Defender, Midfielder, Forward.
2. I randomized data through =rand() function and sorted it.
3. Chose first 300 players through 7000 players and used 80% for training and 20% for testing
4. Calculated centroids for all 4 clusters 
5. Minimized sum distance
6. Ran solver 
7.  I assumed through clusters that GK would be in cluster 1 because it had the highest value in GK_positioning and lowest value in speed and other variables.
I assumed defender would be in cluster 3 because it had the highest marking and strength value. Also, it had a lower value in finishing and ball control.
The midfielder would be in cluster 2 because it had the biggest number in dribbling and ball control.
Forward is in cluster 4 because it had the highest value in finishing and lowest in marking.

In overall I think it is hard to define player positions through their abilities because some defenders have higher values in shooting and finishing than forwards.
Also, some forwards have higher values in speed, acceleration and ball control than midfielders and for those reasons, my accuracy is not close to 100%.

