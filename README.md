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
  
                    train_y = train_x.pop('survived')
                    eval_y  = eval_x.pop('survived')
- This step ensures that the model learns only from relevant input features.
  
## Model Development:
  A machine learning model was developed using TensorFlow. The model was trained on the training dataset to learn survival patterns. After training, the model was tested on evaluation data. This helped in understanding the end-to-end process of model development during the internship.

## Model Evaluation:
- Model predictions were generated on evaluation data.
- Performance analysis was done to understand classification behavior.

## Results and Learning Outcomes:
- Successfully implemented a supervised ML classification model.
- Gained hands-on experience in dataset handling and preprocessing.
- Understood how machine learning can be applied to survival prediction problems.
- Improved practical understanding of TensorFlow-based model training.

## Limitations:
- Basic model architecture
- Limited feature engineering
- No advanced hyperparameter tuning
- Scope for improving accuracy and robustness

## Future Enhancements:
- Apply advanced ML algorithms (Logistic Regression, Random Forest)
- Improve feature engineering and scaling
- Add performance metrics (accuracy, precision, recall, F1-score)
- Deploy the model as a web application
- Work with larger datasets

## Conclusion
This internship project provided valuable practical exposure to machine learning concepts. The project helped bridge the gap between theoretical knowledge and real-world implementation by working on an end-to-end ML pipeline.

## Project Structure
Survival-Prediction/

- │── Survival from a ship.ipynb     -  # Main Jupyter Notebook
- │── train.csv                      -  # Training dataset
- │── eval.csv.xls                   -  # Evaluation dataset
- │── README.md                      -  # Project documentation
- │── requirements.txt               -  # Project dependencies

## Requirements.txt
Pandas, matplotlib, tensorflow


