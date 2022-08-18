# Dataset datasheet

### Motivation
The dataset was downloaded from https://www.kaggle.com/code/niteshyadav3103/red-wine-quality-classification/data?select=winequality-red.csv for practicing regression and classification modeling. However, its primary source at UCI Machine Learning Repository, see the web link bellow in paragraph Distribution.
I chose this dataset because I wanted to use Grid search and Bayesian optimization on divert classifier on a multiclass classification task. From several candidates I found on divert repositories, this one was the cleanest and the most interesting real-life dataset. The original source contains two datasets, one for white wines, the second for red ones. I chose red-wine dataset because of its size and for minimizing computing time during experimentations.

### Composition
The red wine dataset contains 1599 records. There is no any ID related to the records.
Input variables (based on physicochemical tests):
*1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
*

Output variable (based on psycho-sensorial data):
*12 - quality (score between 0 and 10)*

The dataset doesn't contain any missing data, but classes are unbalanced. There are much more normal wines than excellent or poor ones.

### Collection process
The primary source doesn’t provide any information about the data collection. However, some clues might be mentioned in the paper “P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.”, it can be bought at http://dx.doi.org/10.1016/j.dss.2009.05.016

### Preprocessing/cleaning/labeling
The features contain laboratory test results (e.g. pH value). The output variable is based on sensory data (median of at least 3 evaluations made by wine experts). Each expert graded the wine quality between 0 (very bad) and 10 (very excellent).

### Uses
The dataset is mentioned in articles written by P. Cortez, where it was used as data for research in data classification. Other uses are studying purposes.

### Distribution
A Vinho Verde wine quality data set was chosen made available by UCI Machine Learning: https://archive.ics.uci.edu/ml/datasets/wine+quality .

Source: Paulo Cortez, University of Minho, Guimarães, Portugal, http://www3.dsi.uminho.pt/pcortez A. Cerdeira, F. Almeida, T. Matos and J. Reis, Viticulture Commission of the Vinho Verde Region(CVRVV), Porto, Portugal @2009
Several copies of the dataset are on Kaggle and other sites.

A requested citation is needed to use the dataset: “P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.”

### Maintenance
No maintenance information is provided.
