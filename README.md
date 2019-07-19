# Numpy and matplotlib tutorial for beginners using a breastcancer dataset.

## Running this tutorial online:
You can Launch this tutorial on [![Binder](https://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/subhacom/np_tut_breastcancer/master) or [![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/blue?icon=terminal)](https://colab.research.google.com/github/subhacom/np_tut_breastcancer/blob/master/Wisconsin_breast_cancer_data.ipynb).

## Running this tutorial on your own computer:
You need to have Python installed with numpy, matplotlib and pandas libraries. [https://www.anaconda.com/](Anaconda) Python distribution is easy to install and bundles common libraries for scientific computing.
	1. Click the `Clone or download` button. 
	1. Select `Download ZIP`.
	1. Unzip the downloaded zip file into a folder.
	1. Open a terminal (command prompt/anaconda prompt on Windows) and
       go to this folder by entering `cd folder-path` command).
	1. Start jupyter notebook (enter `jupyter notebook`).
	   This will open a browser window showing the contents of the folder.
	1. Click the `Wisconsin_breast_cancer_data.ipynb` file and this
       will open the notebook in a new window or tab of the browser.
	1. In order to run it as slide-show you must install
       [https://rise.readthedocs.io](RISE) module first. Press `Alt+r`
       to toggle slide-show.

## Summary
This tutorial explores basic usage of numpy and matplotlib using this publicly available dataset: http://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin.
- Introduction to jupyter including running it on the cloud.
- Import python modules.
- `numpy` basics
  - array creation, arithmetic, indexing, slicing, reshaping.
  - heterogeneous arrays (structured/record arrays with named fields).
- load data from csv (text) file.
  - (advanced) use `requests` library to retrieve data from the Internet.
  - (advanced) use StringIO to read from string containing the csv data.
  - (basic) specify field names and data types using numpy `dtype`.
  - (basic) specify missing value handling when loading data
  - (basic) check columns for missing values.
- Pandas
  - (basic) load data using Pandas.
  - (basic) accessing rows and columns in Pandas dataframe.
  - (basic) do simple boxplots of dataframe columns.
-matplotlib
  - basic plotting
    - line plot
    - scatter plot
    - histogram
    - box plot
  - legend
  - subplots
- list of other useful modules


## History:
It was originally the first part of a two part workshop on the basics of `numpy`, `matplotlib` and `pandas` for data science. The first version used in the live workshop can be downloaded as an archive here: https://github.com/subhacom/np_tut_breastcancer/releases/tag/v0.1. This notebook may be updated occasionally. 

The second part of the workshop focuses on `pandas` for data science and is available here: https://github.com/bballew/pandas_tutorial.
