## Introduction
To develop a classification model to identify a device has an off set fault or not, regardless of the device. This model can be used to automatically flag a device that is returning faulty data.

## Dataset Overview
The datasets used are into three categories
- Train.csv: This is the dataset that was used to train the model, it contains the target.
- Test.csv: This is the dataset on which the model was applied to, it resembles Train.csv but without the target column.
- This shows the submission format for the competition, with the ‘ID’ column mirroring that of Test.csv and the ‘Signal’ column containing the model predictions. The order of the rows does not matter, but the names of the ‘ID’ must be correct.

## Algorithms Used
- RandomForestClassifier
- CatBoostRegressor

## Diclaimer
This is my submission for the Umojahack-africa-2022-beginner-challenge.

