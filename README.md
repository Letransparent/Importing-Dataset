# Importing-Dataset
Data Acquisition¶

A data set is typically a file containing data stored in one of several formats. Common file formats containing data sets include: .csv, .json, .xlsx etc. The data set can be stored in different places, on your local machine, on a server or a websiite, cloud storage and so on.

To analyse data in a Python notebook, we need to bring the data set into the notebook. In this section, you will learn how to load a data set into our Jupyter Notebook.

In our case, the Automobile Data set is an online source, and it is in a CSV (comma separated value) format. Let's use this data set as an example to practice reading data.

    Data source: https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data
    Data type: csv

The Pandas Library is a very popular and very useful tool that enables us to read various datasets into a data frame; our Jupyter notebook platforms have a built-in Pandas Library so that all we need to do is import Pandas without installing. 
