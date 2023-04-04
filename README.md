# BCI-classification-models

With this porject we tried to solve a BCI classification problem by using different preprocessing methods (PCA, select-k-best, etc.) and algorithms (SVM, KNN, Bayesian classifier) to maximize the performance of each model. We then further used different evaluation methods (balanced accuracy scores, confusion matrices) to determine which model worked best for our given problem. The main result is that generally the SVM performed better than the 2 other models. However, note that the results are not necessarily representive, since changing some steps or methods, might improve the performance of a model significantly

The dataset is the Dataset V from the BCI competition III. In general, it contains precomputed PSD-values for each of the three subjects. Each subjects did one of 3 distinct tasks, which we try to correctly classify in the project. The Datatset provided some training data as well as test data, for which the labels are now publicly available as well. More info about the dataset can be found here: https://www.bbci.de/competition/iii/#data_set_v


