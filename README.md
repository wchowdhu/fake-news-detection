# Fake or Real News?

The goal of this project is to implement a machine learning model able to determine if an article is *fake news* or *real*.


## Install

The project requires latest Python version and the following Python libraries installed   
  - [numpy](https://numpy.org/)
  - [pandas](https://pandas.pydata.org/)
  - [scikit-learn](https://scikit-learn.org/stable/)
  - [matplotlib](https://matplotlib.org/)
  - transformers
  - torch


## Data

The dataset used for this project can be accesssed from [here](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset).

The corpus consists of 2 csv files - 1 file contains articles which are considered as *fake news* and another file contains the articles labeled as *real*.


## Code

The provided Jupyter notebook contains code covering exploratory data analysis, modeling, training, and evaluating model performance.


## Run

All codes were run on Kaggle kernel with a GPU.

To open the .ipynb files in your browser and look at the output of the completed cells, use the following command in your terminal after changing the working directory to the project directory `fake-news-detection`:
```
jupyter notebook <file_name>.ipynb
```
