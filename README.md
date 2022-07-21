## ENG: Titanic
- The aim of the study was to make a prediction of whether a titanic passenger have survived the catastrophe or not
- Train dataset dimension is equal to 891 observations and 12 variables
- Measures of associations enabled me to reduce Sex, Pclass and Embarked_Q variables
- The process of building the optimal model was based on **wrappers** which aim was to do a proper cross-validation and hyperparameters tuning
- Random Forest, AdaBoost and XGBoost were the algorithms that were chosen in this task
- **Due to the fact that errors were made during data mining/exclusion/transformation and due to the use of the AUC metric (where accuracy was required in the competition, but XGboost gave the result equal to 77%), the model WILL BE REDEVELOPED AS SOON AS POSSIBLE**

#### ROC_AUC chart for AdaBoost
![](https://github.com/askovr0n/askovr0n.github.io/blob/master/images/Project_12/titanic.png)
