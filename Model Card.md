# Model card

### Model details
- Developed as part of the final project of PCMLAI course.
- Multiclass classification.
- Classification using KNN, SVM, Decision tree and Tree ensembles including XGBOOST.
- Hyperparameter tuning using Grid search and Bayesian optimization.

### Intended use
- Red wine classification into 3 categories “poor”, “good”, “excellent”.
- Demonstration of Bayesian optimization used for hyperparameter tuning and comparison with Grid search approach.
- Using oversampling to rebalance training data.
- Educational purpose.

### Factors
- Dataset factors:
The dataset consists of 12 columns. 11 are divert chemical wine features acquired by laboratory analysis. The 12th columns contains the output variable with the quality score from in the range 0 – 10. This quality score values were acquired by tasting wines by specialists. Nature of this data is psycho-sensorial and it is expected to be biased. To mitigate the bias a new output variable was created containing only 3 category “poor”, “good”, “excellent”.
As expected, the dataset is imbalanced in term of output variable. Most of items falls in the category “good”, but the frequencies of “poor” and “excellent” are very low. To rebalance the training dataset, oversampling technique is used.

- Computational factors:
Hyperparameter optimization is a time-consuming operation. To accelerate it the model is set to use all the available CPU cores on the machine. No special settings are done for GPU computation.

### Metrics
- Accuracy is used as basic metric for classification success.

### Training data
- Training data split of the source dataset after quality score aggregation into 3 output categories.
- Training data ratio 70%.
- Using oversampling to rebalance data of the 3 output categories.

### Evaluation data
- Test data split of source dataset after quality score aggregation into 3 output categories.
- Test data ratio 30%.

### Quantitative analysis
For all used classifiers the training anf
Scores on training set:


Scores in

### Ethical consideration
- Not applicable.

### Caveats and recommendations
- The imbalance of data needs to be treated.
