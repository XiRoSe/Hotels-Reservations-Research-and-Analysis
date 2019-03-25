# Hotels-Reservations-Research-and-Analysis

About the data:
- 187,848 rows of hotel reservations in different dates.
- 9 columns - 'Snapshot ID','Snapshot Date','Checkin Date','Days','Original Price','Discount Price','Discount Code','Available Rooms','Hotel Name','Hotel Stars'.
- Dates are from 2015/7 to 2016/3.
- All data collected for DataScience Course at Colman.

Our goals:
- Classification Research - Our goal was to learn for a given 'Snapshot Date','Checkin Date','Hotel Name','Day Diff','WeekDay' properties, what Discount Code will satisfy the highest discount price for a reservation (with generalize matter).
- Clustering Research - Our goal was to check for a similar pricing policies for the varied hotels in our data.
- Distributed part - We wanted to implement the Clustering part in a Distributed manner over Hadoop.


## Key Features

  - Data Transformation - in order to fit to the ML Algorithms and Analysis we desired.
  - Data Normalization - in order to get optimized results.
  - Data Cleaning - cleaning the outliers under a chosen confidence level.
  - Preprocessing - in order to explore the data from several different ways.
  - Machine Learning - using Decision Trees, Naive Bayes & Regressors combined.
  - Clustering Techniques - comparing several different weights and algorithms.
  - Visualization - emphasis on showing and understanding our results via several different tools.
  - Distribution - clustering implementaion in PySpark over Hadoop.


## Tech

Our Project involves the following libraries and addons:

* [Python 3.7](https://www.python.org/downloads/release/python-370/) - Python 3.7.0 is the newest major release of the Python language, and it contains many new features and optimizations.
* [Jupyter Notebook](https://jupyter.org/) - The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations and visualizations.
* [Pandas](https://pandas.pydata.org/) - pandas is an open source providing high-performance, easy-to-use data structures and data analysis tools.
* [Matplotlib](https://matplotlib.org/) - Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.
* [seaborn](https://seaborn.pydata.org/) - Seaborn is a Python data visualization library. It provides a high-level interface for drawing attractive and informative statistical graphics.
* [Numpy](http://www.numpy.org/) - NumPy is the fundamental package for scientific computing with Python.
* [SciPy](https://www.scipy.org/) - SciPy is a Python-based ecosystem of open-source software for mathematics, science, and engineering.
* [scikit-learn](https://scikit-learn.org/stable/) - Simple and efficient tools for data mining and data analysis.
* [pydotplus](https://pandas.pydata.org/) - PyDotPlus is an improved version of the old pydot project that provides a Python Interface to Graphviz’s Dot language.
* [Scikit-plot](https://scikit-plot.readthedocs.io/en/stable/) - Scikit-plot is designed to generate quick and beautiful graphs and plots with as little boilerplate as possible for ML.
* [Spark](https://spark.apache.org/) - Apache Spark™ is a unified analytics engine for large-scale data processing.
* [PySpark](https://spark.apache.org/docs/2.2.1/api/python/pyspark.html) - PySpark is the Python API for Spark.


## Previews

- Table Head :
![table_head](https://user-images.githubusercontent.com/33058843/54922944-dbab8480-4f11-11e9-8df7-ea35958b4c18.png)

- Data Pair-plot :
![pair_plot](https://user-images.githubusercontent.com/33058843/54922988-f847bc80-4f11-11e9-8750-7626d9d77f5c.png)

- Dendogram :
![dendogram](https://user-images.githubusercontent.com/33058843/54923021-07c70580-4f12-11e9-9dfc-f31cbafd2d9d.png)




#### This project was made for our Data Science Course and was not made for commercial use :)

#### Made By Matan Avitan, Daniel Levy, Nir Elkayam & Moria Dassha.
