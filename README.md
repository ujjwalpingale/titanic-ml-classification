# Titanic - Machine Learning Classification Project

This repository contains my work on the Titanic survival prediction problem from Kaggle.  
The objective is to build a simple, reliable model that predicts whether a passenger survived the Titanic disaster based on the available features in the dataset.

## Overview

I approached the problem by first exploring the dataset, understanding the columns, checking missing values, and looking at how different features relate to survival. After that, I cleaned the data and focused on a few basic but useful engineered features like extracting titles from names, creating a family size feature, and identifying passengers who were travelling alone.

Most of the preprocessing was done in a straightforward way: filling missing values, converting categories into numerical form, and dropping columns that didn’t add much value.

After preparing the data, I trained a couple of baseline models. Logistic Regression performed slightly better during cross-validation, while Random Forest was also close. I used cross-validation to get an estimate of how well the models generalize.

The final predictions were generated as a `submission.csv` file, which I submitted to Kaggle. The public leaderboard score was 0.72966.

## What’s Included

- Jupyter notebook with the entire workflow  
- Data preprocessing and feature engineering  
- Training and evaluation of Logistic Regression and Random Forest  
- Kaggle submission file  
- Requirements file with the libraries used  

Note: The original `train.csv` and `test.csv` files from Kaggle are not included here.

## How to Run

1. Download `train.csv` and `test.csv` from Kaggle’s Titanic competition.
2. Place both files in the same directory as the notebook.
3. Open `titanic.ipynb` and run the cells in order.
4. A `submission.csv` file will be generated at the end.

## Future Plans

There are a few things I may try later:
- Using models like XGBoost or LightGBM  
- Extracting deck information from the cabin column  
- Creating age and fare bins for better separation  
- Performing hyperparameter tuning  
- Improving the overall pipeline structure  

For now, this project serves as a simple and clear introduction to working with Kaggle competitions and basic machine learning techniques.


