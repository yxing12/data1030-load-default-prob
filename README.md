# Loan Default Probability Predictor

Loan default occurs when a borrower fails to repay a loan according to the terms agreed upon. This is a critical financial concern that not only adversely affects the borrower's credit rating, but also imposes significant consequences on the lending financial institution, including revenue loss, increased operational costs, and potential reputation damage. 

This project aims to employ machine learning techniques to predict loan defaults based on an analysis of the loan’s specifications and the borrower's financials. The model will benefit lenders by providing a data-driven tool to optimize their risk-reward balance, and borrowers by enabling proactive loan management and better loan terms negotiation. Furthermore, by reducing the incidence of unexpected loan defaults, this model contributes to a more stable economic environment and overall economic health.

## Data Source

[Lending Club’s loan data from 2007-2017 adopted from Kaggle.](https://www.kaggle.com/mlfinancebook/lending-club-loans-data) 

Due to limit in the github for the file size, the compiled full dataset cannot be uploaded, but can be accessed via the above link. Alternatively, 20 splited data files of the data has been uploaded to the data folder under 'raw data in multiple files'. All the subsequent results in the jupyter notebook are performed using the actual data (~1.1GB). You should load the full data in case you want to reproduce the results. When finetuning hyperparameters to select the best ML model, a subset of 200,000 datapoints from the full data was used to save computing power.

You can also find description of each features in data/feature_description.xlsx in this repo.

## Prerequisites
You can recreate the python environment using the `data1030.yml` conda environment file by running these two commands in the terminal:

`conda env create -n loan_pred -f data1030.yml`

`conda activate loan_pred`

You should be able to run `src/loan_default_prob_20w.ipynb` now.
