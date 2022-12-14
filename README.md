# Transport_ML
Machine-Learning Project: Transportation Optimization/ Carrier Performance Analysis


The relevance and importance of the chosen features for this example. Pickup Day is the most important feature in the random forest learning. The destination city is holding little importance in this training. 
Pickup Day_cat        0.467967
Carrier name_Cat      0.251714
Delivery Day_cat      0.244717
Distance              0.024766
Destination city_cat  0.010836

Confusion matrix of the transportation days, the most common is 1 day of transportation from the origin to destination. 
[[ 76   0   0   0]
 [  0 640   0   0]
 [  0   0  26   0]
 [  0   0   0 126]]
![image](https://user-images.githubusercontent.com/120400018/207592963-13f0537e-494f-45b2-91ab-f5f5c93ffeaa.png)

Actual and Predicted values per Carrier. 
![image](https://user-images.githubusercontent.com/120400018/207593606-658292da-e9ba-47a5-81e0-ac08d4542dd3.png)


The forest branches voting for the transit days. The carrier number 1 is most likely to delivery the goods in 1 day. 
![image](https://user-images.githubusercontent.com/120400018/207594300-4fd1672e-d8de-4fd8-a8c4-468ea80073a3.png)
