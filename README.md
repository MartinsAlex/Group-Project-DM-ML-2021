# Group-Project-DM-ML-2021
Project Group for HEC UNIL - Group Nvidia


For this project, the goal was to detect the level of difficulty of French texts and to predict its level of difficulty (A1, A2, B1, B2, C1, C2).

Pour déterminer cela nous avons utiliser:

1. Exploratory Analysis
2. Baseline accuracies determination
3. Hyperparameters optimization
4. PCA - Scaling - Stacking
5. CAMEMBERT Implementation

After a cleaning we used 6 models for the calculations and we retained __only 4__ of them. (we drope KNN and Decision Tree).


## Models results (baseline):

|        | Logistic regression | kNN |	Decision Tree  | Random Forests | Ridge | Perceptron |
| ----------- | ----------- | ----------- | ----------- | -----------   | ----------- | ----------- |
| Precision 	 | 0.4688      | 0.3946      | 0.3077       | 0.3924   | 0.4615        | 0.4117 |
| Recall   | 0.4719        | 0.3490   | 0.3117        | 0.3965   | 0.4666        | 0.4095 |
| F1-score    | 0.4664        | 0.3262   | 0.3055        | 0.3843   | 0.4597        | 0.4060 | 
| Accuracy   | 0.4729        | 0.3510   | 0.3125        | 0.3979   | 0.4677        | 0.4104 |

 					
					
