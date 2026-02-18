## Survival Prediction from a Ship using Machine Learning
In this project, I focused on predicting whether a passenger survived a ship disaster or not.
The prediction is performed using historical passenger data and a supervised machine learning approach. 
The project demonstrates a complete ML workflow including data loading, preprocessing, model building, and evaluation.

## Project Overview:
To analyze passenger data related to survival

To separate target and feature variables

To train a machine learning model using training data

To evaluate the model on unseen data

To understand the application of machine learning in classification problems

## Technologies Used:
Python, Pandas – data manipulation and analysis, Matplotlib – basic visualization, TensorFlow – machine learning model, Jupyter Notebook

## Dataset Description:
The project uses two datasets:

1.Training Dataset (train.csv) Used to train the machine learning model.

2.Evaluation Dataset (eval.csv.xls) Used to test and evaluate the model.

## Target Variable:
- survived

- 1 → Passenger survived

- 0 → Passenger did not survive
This column is used as the output label for prediction.

## Data Preprocessing:
- The dataset is loaded using Pandas.
- The target column survived is separated from the feature set using the pop() method.
- Remaining columns are used as input features for the model.
  ------------------ train_y = train_x.pop('survived')
  ------------------ eval_y  = eval_x.pop('survived')
- This step ensures that the model learns only from relevant input features.

