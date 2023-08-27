# Tutorial Data Analytics menggunakan Pandas

Tutorial ini akan mengolah dat atitanic menjadi data yang siap untuk dilakukan pemodelan 

## Prerequisites

1. Download data [here](https://www.kaggle.com/datasets/fossouodonald/titaniccsv)
2. instalasi dengan 'pip install requirements.txt'

## Getting Started
- Dataset splitting
- Training
- Model Validation

## Dataset Splitting

split data into training, validation and test sets

''' code
x_train,y_train, x_test, y_test = dataset_splitting()
x_train.shape, y_train.shape
'''

##  References
1. di scikit-learn documentain