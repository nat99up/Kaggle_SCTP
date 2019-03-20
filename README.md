# Kaggle competition
## Santander Customer Transaction Prediction




#### My lgb param setting
```
param = {
    'bagging_freq': 5,
    'bagging_fraction': 0.333,
    'boost_from_average':'false',
    'boost': 'gbdt',
    'feature_fraction': 0.05,
    'learning_rate': 0.008,
    'max_depth': -1,  
    'metric':'auc',
    'min_data_in_leaf': 80,
    'min_sum_hessian_in_leaf': 10.0,
    'num_leaves': 13,
    'num_threads': 8,
    'tree_learner': 'serial',
    'objective': 'binary', 
    'verbosity': 1
}
```
---

#### Get top 6% in leaderboard
![image](https://github.com/nat99up/Kaggle_SCTP/raw/master/result/Best_score.png)

