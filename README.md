# Gathering Insight from Kickstarter Data

_A project by Team Apple (Data Mining & Machine Learning, HEC Lausanne, Fall 2019)_

## Team Members
* Tarik BACHA
* Florian EMERY
* Nicolas MAUROUX
* Frederic SPYCHER

## Project Structure

### /code
This folder contains **2 Jupyter notebooks**:

* `Kickstarter_notebook_Team_Apple_EDA.ipynb`: the first part of the project; contains an introduction, explanations about the data cleaning process, as well as the exploratory data analysis (EDA).
* `Kickstarter_notebook_Team_Apple_ML.ipynb`: the second part of the project; contains the various machine learning models trained in the course of this project, with some conclusions.
    * **NB**: Keras and Tensorflow have to be installed for the neural network to run.

As well as **2 Python codes**:
* `cleaning.py`: contains the cleaned version of the dataset, imported in the ML notebook.
* `custom_functions.py`: in order to make it easier to play with feature selection and scaling/encoding types, a custom _train_test_split_ function was implemented in this file. Parameters:
    * `data`: pandas DataFrame containing the dataset
    * `predict`: feature to use as dependent variable
    * `rseed`: random seed for the _train_test_split_ function
    * `scaling`: scaling scheme for numerical values ("std" for z-score normalization, "minmax" for min-max normalization)
    * `encoding`: encoding scheme for categorical values ("onehot" for one-hot encoding, "label" for label encoding)
    * `features`: array of features to be used as independent variables

### /data
This folder contains the original dataset, retrieved from [https://kaggle.com/kemical/kickstarter-projects](https://kaggle.com/kemical/kickstarter-projects).

### /documents
This folder contains:

* The final PowerPoint presentation
* `ml_results.xlsx`: an Excel document containing an overview of each machine learning model's scores with various features and types of scaling (standard/min-max) and encoding (one-hot/label).
