# Modeling

When you are happy with your model, treat also the validation set as part of the training set as re-do the training process to use 100% of the training set to further improve the result. \(per Jeremy\)

[Thenerdstation/mltest: Testing framework to simplify writing ML unit tests.](https://github.com/Thenerdstation/mltest)

[Comet.ml \| Supercharging Machine Learning](https://www.comet.ml/)

When you are happy with your model, treat also the validation set as part of the training set as re-do the training process to use 100% of the training set to further improve the result. \(per Jeremy\)

[A Deep Dive Into Sklearn Pipelines \| Kaggle](https://www.kaggle.com/baghern/a-deep-dive-into-sklearn-pipelines/code)

## Basic Error Analysis \(From Machine Learning Yearning\)

> * When you start a new project, especially if it is in an area in which you are not an expert,  it is hard to correctly guess the most promising directions.
> * So don’t start off trying to design and build the perfect system. Instead build and train a   basic system as quickly as possible—perhaps in a few days. Then use error analysis to   help you identify the most promising directions and iteratively improve your algorithm   from there.
> * Carry out error analysis by manually examining ~100 dev set examples the algorithm   misclassifies and counting the major categories of errors. Use this information to   prioritize what types of errors to work on fixing.
> * Consider splitting the dev set into an Eyeball dev set, which you will manually examine,   and a Blackbox dev set, which you will not manually examine. If performance on the   Eyeball dev set is much better than the Blackbox dev set, you have overfit the Eyeball dev   set and should consider acquiring more data for it.
> * The Eyeball dev set should be big enough so that your algorithm misclassifies enough   examples for you to analyze. A Blackbox dev set of 1,000-10,000 examples is sufficient   for many applications.
> * If your dev set is not big enough to split this way, just use an Eyeball dev set for manual   error analysis, model selection, and hyperparameter tuning.



