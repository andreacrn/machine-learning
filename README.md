# Machine Learning
Project of *Machine Learning* course, Data Science and Business Informatics - University of Pisa

A. Carnevale, F. Canepuzzi, G. Segurini

## Introduction
For this project it is required to solve a regression task on the CUP dataset. It is focused on
trying out the different models, selecting the best hyperparameters configuration and compare
their performances. We used: KNN, SVM, LBE, Random Forest and Neural Network. These
models were first used to perform a classification task on the well-known MONK dataset as
a benchmark. Finally, we implemented from scratch a Stacking and a Voting ensemble by
combining the tuned estimators above.

## Simple models results
Performance of the models evaluated with a Crossvalidated approach

![result](https://user-images.githubusercontent.com/63819344/179366228-9462cead-cd7a-4b0a-a2b9-23bc16a13674.png)

## Ensemble models results

Performance of the ensembles using as base estimators a subset of the models above

![ensamble](https://user-images.githubusercontent.com/63819344/179366242-b271fd0c-8d51-41f1-a733-f397e83c2a0d.png)
