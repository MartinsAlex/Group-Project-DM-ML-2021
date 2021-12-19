# [Detecting the difficulty level of French texts](https://www.kaggle.com/c/detecting-the-difficulty-level-of-french-texts/overview/evaluation)
## Project Group for the Data Mining & Machine Learning course, at HEC UNIL (Group Nvidia)

For this project, the goal was to detect the level of difficulty of French texts and to predict its level of difficulty (A1, A2, B1, B2, C1, C2).

To determine this we went through different steps:

1. Exploratory Analysis
2. Baseline accuracies determination
3. Hyperparameters optimization
4. PCA - Scaling - Stacking
5. CAMEMBERT Implementation


## Models results (baseline):

|        | Logistic regression | kNN |	Decision Tree  | Random Forests | Ridge | Perceptron |
| ----------- | ----------- | ----------- | ----------- | -----------   | ----------- | ----------- |
| Precision 	 | 0.4688      | 0.3946      | 0.3077       | 0.3924   | 0.4615        | 0.4117 |
| Recall   | 0.4719        | 0.3490   | 0.3117        | 0.3965   | 0.4666        | 0.4095 |
| F1-score    | 0.4664        | 0.3262   | 0.3055        | 0.3843   | 0.4597        | 0.4060 | 
| Accuracy   | 0.4729        | 0.3510   | 0.3125        | 0.3979   | 0.4677        | 0.4104 |


## Final accuracies (after hyperparameters tuning):

|        | Logistic regression | Random Forests | Ridge | Perceptron |
| ----------- | ----------- |  -----------   | ----------- | ----------- |
| Accuracy   | 0.5031        |     | 0.4198   | 0.4677        | 0.4104 |

You can know more about our pathway, with reading these notebooks, in this order:

1. [EDA.ipynb](http://github.com/LaCrazyTomato/Group-Project-DM-ML-2021/blob/main/code/EDA.ipynb)
2. [first_approach.ipynb](http://github.com/LaCrazyTomato/Group-Project-DM-ML-2021/blob/main/code/first_approach.ipynb)
3. [hyperparameters_tuning.ipynb](http://github.com/LaCrazyTomato/Group-Project-DM-ML-2021/blob/main/code/hyperparameters_tuning.ipynb)
4. [model_improvments.ipynb](http://github.com/LaCrazyTomato/Group-Project-DM-ML-2021/blob/main/code/model_improvement.ipynb)
5. [bert_implementation.ipynb](http://github.com/LaCrazyTomato/Group-Project-DM-ML-2021/blob/main/code/bert_implementation.ipynb)					
					
