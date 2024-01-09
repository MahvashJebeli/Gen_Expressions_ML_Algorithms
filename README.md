## Investigated a large genomics dataset of different cancer line’s gene expressions to predict cancer type.
* Utilized scikit-learn, pandas, and NumPy libraries in Python.
* SVM and clustering algorithms (with PCA) were employed.
* Large genomic datasets
* Unsupervised Learning and SVM

### My practice code from solving ISLR: Data for an Introduction to Statistical Learning book problems
#### In Gene Expressions _ Cancer Lines _ Khan Dataset _ SVM.ipynb code:
* Using support vector approach to predict cancer subtype using gene expression measurements.
* Large number of features relative to the number of observations (83), so using Linear Kernel to avoid overfitting.
##### - SVM using [ISLR dataset Khan (compatible with Python)](https://github.com/emredjan/ISL-python/tree/master/datasets)
* Khan dataset consists of a number of tissue samples corresponding to four distinct types of small round blue cell tumors.
* For each tissue sample, gene expression measurements are available.
* This data set consists of expression measurements for 2,308 genes.

#### In Gene Expressions _ Cancer Lines _ NCI60 _ PCA _ Clustering.ipynb code:
* Using PCA for dimension reduction, then clustering to predict cancer type.
* Not using the cancer types in performing PCA and clustering, as these are unsupervised techniques.
##### - Clustering and PCA using [ISLR dataset NCI60](https://github.com/emredjan/ISL-python/tree/master/datasets)
* NCI60 consists of 6,830 gene expression measurements on 64 cancer cell lines.

