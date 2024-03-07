# Cars with Manufactored Years from 1970 to 2024
Link to the dataset is [here](https://www.kaggle.com/datasets/meruvulikith/90000-cars-data-from-1970-to-2024). 
I'm interested in using automobiles and am curious about how to use this data to train machine learning models. 
The goal is to explore the data and identify possible machine learning models to use.

# Summary
The `cars` dataset contains roughly 97,000 cars that were manufactored between 1970 and 2024 from well-known manufactorers like BMV, Ford, Volkswagon, etc.
Upon exploring the relationships between different columns, many relationships are either non-existent or non-linear. From my initial research, I concluded that non-linear machine learning models are a possible choice.
I selected polynomial regression because it's an easy-to-understand model that deals with non-linear relationships. As a result, I realized from the performance evaluation using mean absolute error, mean squared error, and root mean squared error that the model is not doing well.
Next steps is to revise my approach to how I feed the data to a model. Depending on the approach, I would then have to select a different model. 
