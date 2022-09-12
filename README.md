# Faulty-Air-Quality_Sensor_Challenge

## Overview
Developed a multi-class classification model to identify and classify faults according to their categories specified. The model can be used by AirQo to automatically flag a device that is returning faulty data. 

## About the data
The datasets used are into three categories
- Train.csv: This is the dataset that was used to train the model, it contains the target.
- Test.csv: This is the dataset on which the model was applied to, it resembles Train.csv but without the target column.
- This shows the submission format for the competition, with the ‘ID’ column mirroring that of Test.csv and the ‘Signal’ column containing the model predictions. The order of the rows does not matter, but the names of the ‘ID’ must be correct.

## Algorithms Used
- RandomForestClassifier
- CatBoostRegressor

## Acknowledgment
- [Umojahack](https://www.bing.com/videos/search?q=umojahack+faulty+air+quality+sensor&cvid=242882021a69458f9ef0e45b2b67e3ed&aqs=edge..69i57j69i64.49045j0j1&pglt=171&PC=U531&ru=%2fsearch%3fq%3dumojahack%2bfaulty%2bair%2bquality%2bsensor%26cvid%3d242882021a69458f9ef0e45b2b67e3ed%26aqs%3dedge..69i57j69i64.49045j0j1%26pglt%3d171%26FORM%3dANNTA1%26PC%3dU531&view=detail&mmscn=vwrc&mid=0643C0E5F339CEE221D30643C0E5F339CEE221D3&FORM=WRVORC)

- [Zindi](https://zindi.africa/competitions/?kind[]=hackathon)

