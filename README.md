# Big Data Analytics_Homework2
#
## XGBoost
一開始先調max_depth, min_child_weight
max_depth: [3, 4, 5, 6]
min_child_weight:[1, 3, 5, 7]
(Cross Validated = 5)

##### Result
![](http://imgur.com/udO0HEm.png)
最好的參數為max_depth=5, min_child_weight=1
##### Heatmap
![](http://imgur.com/7H9G1ZA.png)

再調n_estimators, gamma
n_estimators:[100, 120, 140, 160, 180]
gamma: [0.0, 0.1, 0.2]
(Cross Validated = 5)

##### Result
![](http://imgur.com/wN8VdAL.png)
最好的參數為n_estimators=120, gamma=0.0
##### Heatmap
![](http://imgur.com/NJHOTQ6.png)

## Gradient Boosting
一開始先調min_samples_split, max_depth
min_samples_split:[200, 400, 600, 800]
max_depth:[5, 7, 9]
(Cross Validated = 3)

##### Result
![](http://imgur.com/xqRTO45.png)
最好的參數為min_samples_split=200, max_depth=9
##### Heatmap
![](http://imgur.com/32uUjGK.png)

再調n_estimators, min_samples_leaf
n_estimators:[100, 120, 140, 160, 180, 200]
min_samples_leaf: [20, 30, 40, 50, 60, 70]
(Cross Validated = 5)

##### Result
![](http://imgur.com/XKixJPy.png)
![](http://imgur.com/oeeEZau.png)
最好的參數為n_estimators=200, min_samples_leaf=20
##### Heatmap
![](http://imgur.com/gg8aPJ8.png)