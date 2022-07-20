# AIS-Summer-Comp
A repository to track my TAMS AIS summer competition notebooks and entries

(Scores are RMSE, lower is better)

1. RandomForestRegressor: 147456
2. RandomForestRegressor - improvement over #1: 145k
3. XGBoost with guessed hyperparams - no improvement: 166k
4. XGBoost with tuned hyperparams (file lost) - no improvement: 160k
5. XGBoost with retuned hyperparams - no improvement: 150k
6. XGBoost with gradient boosting and tuned hyperparams - no improvement: 167k
7. RandomForestRegressor Pipeline with tuned hyperparams and scaling - no improvement: 154k
8. RandomForestRegressor Pipeline with tuned hyperparams - no improvement: 153k
9. RandomForestRegressor Pipeline with scaling, minor hyperparam tuning - improvement over #2: 143k
10. RandomForestRegressor Pipeline with scaling, more tuned hyperparams - no improvement: 148k
11. RandomForestRegressor with columns removed due to less correlation - improvement over #9: 133k
12. RandomForestRegressor with with scaled data and columns removed - no improvement: 134k
13. (failed submission) RandomForestRegressor utilizing the ID column through pandas get_dummies()
14. RandomForestRegressor with ID column used - improvement over #11: 74k
15. RandomForestRegressor with ID column used and tuned hyperparameters - improvement over #13: 74k

