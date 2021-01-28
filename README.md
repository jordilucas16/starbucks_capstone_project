# Starbucks capstone project

Starbucks capstone project belongs to Udacity Data Science Nanodegree program.

## Motivation

The main motivation for the development of this project is to provide a consistent and valid model that allows the creation of interest offers for the clients of any company, in this case starbucks.

## Resources


The project has the following different resources in file form:

The analysis, cleaning, data exploration and construction of models based on the dataset created as a result of the previous steps is divided into two files that should be executed in the following order:

#### Jupyter Notebooks

`Starbucks_Capstone_notebook1.ipynb`

`Starbucks_Capstone_Challenge_Building models.ipynb`

#### Datasets

On the other hand, the initial datasets used for this project are the following:

data/`portfolio.json`: containing offer ids and meta data about each offer (duration, type, etc.)

data/`transcript.json`: records for transactions, offers received, offers viewed, and offers completed

data/`profile.json`: demographic data for each customer


As a result of the data wranglig and feature engineering operations, two new datasets are created:

data/`portfolio_cleaned.csv`: processed information related to initial portfolio dataset

data/`combined_data.json`: dataset prepared and built in the first notebook with the objective of building the classification models

## Libraries

* [Python Data Analysis Library: pandas](https://pandas.pydata.org/)

* [Numpy: The fundamental package for scientific computing with Python](http://www.numpy.org/)

* [Matplotlib: comprehensive library for creating static, animated, and interactive visualizations in Python](https://matplotlib.org/)

* [seaborn: Statistical Data Visualization](https://seaborn.pydata.org/)

* [re: Regular expression operations](https://docs.python.org/3/library/re.html)

* [scikit-learn: Machine Learning in Python](https://scikit-learn.org/stable/)

* [scipy: Python-based ecosystem of open-source software for mathematics, science, and engineering](https://www.scipy.org/)

* [progressbar: Provide visual (yet text based) progress to long running operations.](https://pypi.org/project/progressbar2/)

* [Joblib: running Python functions as pipeline jobs](https://joblib.readthedocs.io/en/latest/)

## Summary analysis

To find the best possible model, three different supervised classification algorithms have been used:

* Logistic Regression
* Gradient Boosting
* Random Forest

This are the table of metric of them:

|                 | Log. Regression | Gradient Boosting | Random Forest  |
| -------------   |:---------------:| -----------------:| --------------:|
| accuracy        | col 3 is        | right-aligned     | $1600          |
| f1score         | col 2 is        | centered          |   $12          |
| precission      | zebra stripes   | are neat          |    $1          |
| recall          | zebra stripes   | are neat          |    $1          |

## Acknowledgements


These are the main resources, including websites, books or papers that have helped me to find solutions and develop this project.

* [Hands-on ML with Scikit-Learn, Keras and Tensorflow by Aurélien Géron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
* [AUC-ROC curve](https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc)
* [Markdown: Create tables](https://www.makeuseof.com/tag/create-markdown-table/)

You can find more information by reading my technical article on Medium.
