# Source codes and datasets
Datasets and codes for the paper: "Chemical Hardness-Driven Interpretable Machine Learning Approach for Rapid Search of Photocatalysts" (https://doi.org/10.1038/s41524-021-00669-4)

This Github repository contains datasets and Jupyter notebooks for the following tasks (as a proof-of-concept):

1) Feature ranking for formation energy predictions using elemental and chemical hardness-based features
2) Selecting best performing ML algorithm using PyCaret (for formation energy predictions using elemental and chemical hardness-based features)
3) Bayesian hyperparameter optimization using Optuna (for formation energy predictions using elemental and chemical hardness-based features)
4) Finding best ML model (for formation energy predictions using elemental and chemical hardness-based features)
5) SHAP feature importance plot, dependence plots, and force plots for formation energy predictions using elemental and chemical hardness-based features
6) Plotting ROC-AUC curve and confusion matrix of the best ML model obtained for multiclass classification of overall stability
7) SHAP feature importance plot and multioutput decision plot for multiclass classification of overall stability

## Python packages required
1) Scikit-learn
2) Numpy
3) Optuna
4) PyCaret
5) SHAP
6) imblearn
7) LightGBM

## How to cite

Please cite the following paper if you intend to use our codes in some form:
@article{Kumar_2021,
doi = {10.1038/s41524-021-00669-4},
url = {https://doi.org/10.1038/s41524-021-00669-4},
year = 2021,
month = {dec},
publisher = {Springer Science and Business Media {LLC}},
volume = {7},
number = {1},
pages = {197},
author = {Ritesh Kumar and Abhishek K. Singh},
title = {Chemical hardness-driven interpretable machine learning approach for rapid search of photocatalysts},
journal = {npj Comput. Mater.}
}
