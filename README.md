# HyperparameterPipeline_Tutorial
TL;DR Tutorial notebook for hyperparameter tuning for a model set using Pipeline

This notebook was created for a workshop as part of the Insight Data Science Fellowship (Fall 2020) that I led with another fellow. It presents a basic walk through of the creation of a model fitting pipeline that uses a randomized search to tune hyperparameters. 

The dataset used is the Wine Quality dataset in the UCI Repository (https://archive.ics.uci.edu/ml/datasets/wine+quality) which contains several numeric features of physicochemical and sensory qualities of wine. To provide examples of basic binary classification models, the class labels were turned from an ordinal multiclass label to a binary label (quality <= 5 = 'bad', quality >5 = 'good'). 

The notebook also contains code for decision tree visualization using dtreeviz.

No EDA or data balancing are performed here (although if this was a real analysis they would be!) 
