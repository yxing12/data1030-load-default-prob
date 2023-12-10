# Loan Default Probability Predictor

Loan default occurs when a borrower fails to repay a loan according to the terms agreed upon. This is a critical financial concern that not only adversely affects the borrower's credit rating, but also imposes significant consequences on the lending financial institution, including revenue loss, increased operational costs, and potential reputation damage. 

This project aims to employ machine learning techniques to predict loan defaults based on an analysis of the loan’s specifications and the borrower's financials. The model will benefit lenders by providing a data-driven tool to optimize their risk-reward balance, and borrowers by enabling proactive loan management and better loan terms negotiation. Furthermore, by reducing the incidence of unexpected loan defaults, this model contributes to a more stable economic environment and overall economic health.

## Data Source
**Accessing the Complete Dataset**
The complete dataset used in this project is Lending Club’s loan data from 2007-2017, which can be accessed from Kaggle: [Lending Club Loans Data on Kaggle](https://www.kaggle.com/datasets/mlfinancebook/lending-club-loans-data). This dataset is comprehensive and spans approximately 1.1GB in size.

**Dataset Availability and Split Files**
Due to GitHub's file size limitations, the full compiled dataset is not uploaded there. However, it is accessible through two alternative means:

1. Directly from the provided Kaggle link.
2. Via a [Google Drive link](https://drive.google.com/file/d/1QhtFHRheKtgRZ7khOfqPVkOtCToWJE_N/view?usp=drive_link).
3. For convenience, the dataset has also been split into 20 smaller CSV files, which are available in the 'raw data in multiple files' folder under 'data' in this GitHub repository.

**Working with the Data**
To reproduce the results shown in the Jupyter notebook, it is recommended to use the full dataset. For the fine-tuning of hyperparameters in the machine learning models, a subset of 200,000 data points from the full dataset was utilized to save on computing resources.

**Additional Resources**
In this repository, you will also find a file 'data/feature_description.xlsx', which provides a detailed description of each feature in the dataset.

**Oversized Files and Intermediate Data**
Some files that are too large for GitHub, including the original full data CSV file, a cleaned data pickle file, and four machine learning model pickle files saved from cross-validation, are available at the [Google Drive link](https://drive.google.com/drive/folders/1FngPTxSwXr94BdEPl0Mf_S_X9xuLAhHF?usp=drive_link).

## Prerequisites
You can recreate the python environment using the `data1030.yml` conda environment file by running these two commands in the terminal:

`conda env create -n loan_pred -f data1030.yml`

`conda activate loan_pred`

You should be able to run `src/loan_default_prob_20w.ipynb` now.
