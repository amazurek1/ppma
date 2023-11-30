# Paper Summary
![Picture1](https://github.com/amazurek1/ppma/assets/51759577/fcfd9376-1e7a-4440-adea-b028de663358)
<br>
The primary objective of the research paper and the models developed at Boehringer Ingelheim is to accurately predict the percent monomer of a given antibody. This prediction is based on the sequence, germline, and format information associated with each antibody.

# Repo Summary
<br>
This code is designed to compute the features outlined in the methods section of the research paper, "Predicting the Purity of Multispecific Antibodies from Sequence Using Machine Learning". It includes a step-by-step guide on how to transform raw antibody data into features suitable for a Machine Learning model.

**example_data.csv**
<br>
This file contains data for two sample antibodies. Each row represents an antibody, and the columns provide the raw features of the antibody. These features include heavy chain and light chain sequences, germlines and germline pairs, format, and lab result percent monomer (the target variable to be predicted).

**Kabat_data.csv**
<br>
This data corresponds to the same antobodies in the example_data.csv, and contains the individual framework and CDR component split ups for each sequence in the example_data.csv

**Code_ALong_for_Paper.ipynb**
<br>
This Jupyter notebook processes the "example_data.csv" and "kabat.csv" datasets to transform the raw data into features suitable for use as input in a Machine Learning model. The outcome of this code-along tutorial is a set of features that can be readily utilized for training and evaluating Machine Learning models.

The code along helps work through the raw data to get to the features to make it easier for others to use this method of featurization for modeling. We do not include the data that was used in the paper, but we do include two sample data points to make the code along easier to follow. At the end of the code along you should be able to feature select and run models on other datasets.
