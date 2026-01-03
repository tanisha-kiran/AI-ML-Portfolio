Day 11 – Power Transformers
Topics Learned:
Power Transformation techniques:
Box-Cox Transformer
Yeo–Johnson Transformer
Box-Cox does not work when:
Data contains zero values
Data contains negative values
To handle such cases, Yeo–Johnson is used

Day 12 – Encoding Numerical Features
Topics Learned:
discretization
Binarization
Discretization methods:
Unsupervised:
Equal Width
Equal Frequency
K-Means Binning
Supervised:
Decision Tree Binning
Custom Binning

Day 13 – Handling Mixed Data
Topics Learned:
Mixed data contains both numerical and categorical values
Handling method:
Split into separate columns using Pandas
Treat numerical and categorical features independently

Day 14 – Missing Data (CCA)

Topics Learned:

Complete Case Analysis (CCA)

Used when:

Missing values are < 5%

Data is missing randomly

Entire row is removed if it meets conditions

Day 15 – Univariate Imputation

Topics Learned:

Mean & Median Imputation:

Mean → for normally distributed data

Median → for skewed data

Drawbacks:

Can distort data distribution

Reduces variance

Affected by outliers

Day 16 – Multivariate Imputation

Topics Learned:

KNN Imputer

Finds k-nearest neighbors

Fills missing values with their mean

Iterative Imputer

Fills missing values using ML prediction

Repeats until change becomes negligible

Intro to Outliers

Day 17 – Outlier Detection

Topics Learned:

Outliers = data behaving abnormally

Detection using Z-Score

Only valid for normally distributed data

Outlier treatment:

Trimming – remove outliers

Capping – limit values inside a range

Day 18 – IQR Method

Topics Learned:

Z-score fails on skewed data

Interquartile Range (IQR):

Outliers detected using:

Q1 − 1.5×IQR

Q3 + 1.5×IQR

Day 19 – Percentile & Winsorization

Topics Learned:

Percentile based outlier handling

Winsorization = percentile capping

Intro to Deep Learning & Turing Machines (theory revision)

Day 20 – Feature Engineering & Curse of Dimensionality

Topics Learned:

Feature Construction

Feature Splitting

Curse of Dimensionality:

High dimensions cause sparsity

Distance-based models degrade (KNN, SVM)

Solutions:

Feature Selection

Feature Extraction (PCA etc.)

Reflection:

How LLMs deal with high dimensionality
