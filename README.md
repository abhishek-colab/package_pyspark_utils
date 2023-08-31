# package_pyspark_utils

A Python package to perform a small collection of functions on pyspark DataFrames. It contains the following functions:

- data_prep:
  - prepare_data: This function prepares data to be fed to a ml model. Performs indexing and one hot encoding on categorical columns.

- train:
  - train_model: This function trains a machine learning model
 
- evaluate:
  - evaluate_model: This function evaluates a trained machine learning model

## How to install the package:
To install this package, run the following command:
```
pip install git+https://github.com/abhishek-colab/package_pyspark_utils
```
In case if you are facing issues while installing from the above command, you can downlowad the whl file and use the following command
```
pip install PATH/TO/pyspark_utils-0.0.1-py3-none-any.whl
```
