# Transaction-Prediction-Using-Random-Forest
This repo contains transactional data prediction analysis using random forest. The dataset is realworld transactional dataset with, highly imbalanced dependent variable. It is binary classification, where 0 is no transaction on a given date, whilist 1 is there is transaction on a given date. The main challenge of this project is data imbalance. I have tried random forest model with grid search method to find optimized combinations of hyperparameters, along with undersampling approach. Random forest is computationaly expensive as it generates and combines the result of multipl trees. Hence, I have choosen to undersample the dataset, rather than oversampling. 
