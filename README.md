# Numpy and matplotlib tutorial for beginners using a breastcancer dataset.

You can Launch this tutorial on [![Binder](https://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/subhacom/np_tut_breastcancer/master) or [![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/blue?icon=terminal)](https://colab.research.google.com/github/subhacom/np_tut_breastcancer/blob/master/Wisconsin_breast_cancer_data.ipynb).

It is the first part of two part workshop on the basics of `numpy`, `matplotlib` and `pandas` for data science.

The second part focuses on `pandas` and is available here: https://github.com/bballew/pandas_tutorial.
This will be updated occasionally. The original version used in the live workshop can be downloaded as an archive here: https://github.com/subhacom/np_tut_breastcancer/releases/tag/v0.1.

This tutorial explores basic usage of numpy and matplotlib using a publicly available dataset: http://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin.
- import python modules.
- numpy basics
  - array creation, indexing, slicing, reshaping, arithmetic
  - heterogeneous arrays (structured/record arrays with named fields)
- load data from csv (text) file.
  - (advanced) use `requests` library to retrieve data from the Internet
  - (advanced) use StringIO to read from string containing the csv data
  - (basic) specify field names and data types using numpy `dtype`.
  - (basic) load data using Pandas.
-matplotlib
  - basic plotting
    - line plot
    - scatter plot
    - histogram
    - box plot
  - legend
  - subplots
- list of other useful modules  
