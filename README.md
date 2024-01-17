# BinaryClassification-IMDbDataset

This Project contains a walkthrough for diverse machinelearning models for binary classification.The Dataset used for the project is [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
which contains 50 thousand movie reviews classed as 0 (Negative ) and 1(Positive). The notebook is also available on kaggle (Binary Classification On IMDb Dataset)[https://www.kaggle.com/code/kianindeed/binary-classification-on-imdb-dataset]. It contains various sections starting from visualizing data to train on multiple classical machine learning models.
```
max_features/max_len = 2000
max_iter = 500 (LR/MLP)
max_iter = 100000 (SVC)
hidden_layer_sizes=(300) (MLP)
```




|Model   | Accuracy |
|--------|----------|
|LR      | 86.25%   |   
|MLP     | 85.70%   |
|SVC     | 86.44%   |
|Bi-LSTM | 87.65%   |   
