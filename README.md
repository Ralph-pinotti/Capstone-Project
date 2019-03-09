## Download datasets

Navigate to https://www.kaggle.com/c/home-credit-default-risk/data

Press the "Download All" button

When finished downloading unzip the all.zip into the git repo's input/ directory.

## Capstone proposal review

For capstone proposal review click in link below

https://review.udacity.com/#!/reviews/1635715


# Notebook description:

## Notebook 1: Train_Test_bureau_data

I will follow the road map

  1 - Import the data

  2 - Exploratory data analysis

  3 - Label encoding

  4 - One hot encoding

  5 - Feature Engineering

  6 - Dropping correlated features (> 0.6)

  7 - Dropping missing features (> 0.6)

  8 - Run Logistic regression to be the benchmark

  9 - Run RandomForestClassifier to get features importance

  10 - Run first time Light GBM

## Notebook 2: Bureau_data

  1 - Import the data (Bureau and Bureau_Balance)

  2 - Exploratory data analysis

  3 - Label encoding

  4 - One hot encoding

  6 - Dropping correlated features (> 0.6)

  7 - Dropping missing features (> 0.6)

  9 - Run RandomForestClassifier to get features importance

  10 - Run Light GBM (to know if performance is getting better)


# Notebook 3: Auxiliar data

1 - Import the data (Previous_application, Pos_cash_balance, instalments_payments and credit_card_balance)

2 - Exploratory data analysis

3 - Label encoding

4 - One hot encoding

6 - Dropping correlated features (> 0.6)

7 - Dropping missing features (> 0.6)

9 - Run RandomForestClassifier to get features importance

10 - Run Light GBM (to know if performance is getting better)

# Notebook 4: Final_table

1 - Import all table created in the notebook 1, 2 and 3

2 - Concatenate all table in train_table and Test_table

3- Dropping correlated features (> 0.6)

4 - Dropping missing features (> 0.6)

5 - Run Logistic regression

6 - Run RandomForestClassifier to get features importance

7 -  Run ligthGBM

8 -  Run ligthGBM with tuning parameter


## Software used in project

### Python
Python is a great object-oriented, interpreted, and interactive programming language. It is often compared (favorably of course :-) ) to Lisp, Tcl, Perl, Ruby, C#, Visual Basic, Visual Fox Pro, Scheme or Java... and it's much more fun.

Python combines remarkable power with very clear syntax. It has modules, classes, exceptions, very high level dynamic data types, and dynamic typing. There are interfaces to many system calls and libraries, as well as to various windowing systems. New built-in modules are easily written in C or C++ (or other languages, depending on the chosen implementation). Python is also usable as an extension language for applications written in other languages that need easy-to-use scripting or automation interfaces.

For more information:
https://wiki.python.org/moin/FrontPage

Used version Python 3

### The Jupyter Notebook

The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.

For more information: https://jupyter.org/

# libraries

## NumpY
NumPy is the fundamental package for scientific computing with Python. It contains among other things:

  * A powerful N-dimensional array object
  * Sophisticated (broadcasting) functions
  * Tools for integrating C/C++ and Fortran code
  * Useful linear algebra, Fourier transform, and random number capabilities

Besides its obvious scientific uses, NumPy can also be used as an efficient multi-dimensional container of generic data. Arbitrary data-types can be defined. This allows NumPy to seamlessly and speedily integrate with a wide variety of databases.

For more information:http://www.numpy.org/

## Pandas

pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

The purpose of the Project Governance documents is to formalize the governance process that the pandas project has used informally since its inception in 2008. The documents clarify how decisions are made and how the various elements of our community interact, including the relationship between open source collaborative development and work that may be funded by for-profit or non-profit entities.


For more information:https://pandas.pydata.org/about.html

## SKLearn

### SkLearn Preprocessing

The sklearn.preprocessing package provides several common utility functions and transformer classes to change raw feature vectors into a representation that is more suitable for the downstream estimators.

In general, learning algorithms benefit from standardization of the data set. If some outliers are present in the set, robust scalers or transformers are more appropriate. The behaviors of the different scalers, transformers, and normalizers on a dataset containing marginal outliers is highlighted in Compare the effect of different scalers on data with outliers.

For more information:https://scikit-learn.org/stable/modules/preprocessing.html

### SKLern Ensemble methods

The goal of ensemble methods is to combine the predictions of several base estimators built with a given learning algorithm in order to improve generalizability / robustness over a single estimator.

#### Random forest classifier

A random forest classifier.

A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. The sub-sample size is always the same as the original input sample size but the samples are drawn with replacement if bootstrap=True (default).

## Matplotlib

Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.Matplotlib tries to make easy things easy and hard things possible. You can generate plots, histograms, power spectra, bar charts, errorcharts, scatterplots, etc., with just a few lines of code. For examples, see the sample plots and thumbnail gallery.

For simple plotting the pyplot module provides a MATLAB-like interface, particularly when combined with IPython.
For more information:https://matplotlib.org/

## Seaborn

Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
For more information:https://seaborn.pydata.org/

## Light GBM

LightGBM is a gradient boosting framework that uses tree based learning algorithms. It is designed to be distributed and efficient with the following advantages:

* Faster training speed and higher efficiency.
* Lower memory usage.
* Better accuracy.
* Support of parallel and GPU learning.
* Capable of handling large-scale data.

For more information: https://lightgbm.readthedocs.io/en/latest/
