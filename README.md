# Analysis of Used Cars Data With Manufactored Years 1970 to 2024 in the United Kingdom
In the automobile industry, the data usually consists of the name of manufacturers, a car's characteristics like make, model, year, the price of a car, etc. Upon researching for an automobile dataset to explore, I found a dataset containing roughly 97,000 used cars in the United Kingdom with manufactored years from 1970 to 2024. The link to the dataset is [here](https://www.kaggle.com/datasets/meruvulikith/90000-cars-data-from-1970-to-2024). My project's goal is to identify a suitable machine learning model to train using this dataset.

## Summary - Round 1
Upon exploring the relationships between different columns, many relationships are either non-existent or non-linear. From my initial research, I concluded that non-linear machine learning models are a possible choice. I selected polynomial regression because it's an easy-to-understand model that deals with non-linear relationships. As a result, I realized from the performance evaluation using mean absolute error, mean squared error, and root mean squared error that the model is not doing well. Next steps is to revise my approach to how I feed the data to a model. Depending on the approach, I would then have to select a different model. 

## Summary - Round 2
From my observation on `Cars.ipynb` in round 1, the dataset from Kaggle consists of both numerical and categorical data. Additionally, there's no relationships between the majority of the presented variables. Finally, this data's characteristics align with unlabelled data. The goal for this round is to determine a suitable action to take in order to use this data to train a machine learning model.
