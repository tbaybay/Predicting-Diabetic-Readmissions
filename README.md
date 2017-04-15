# Diabetics Readmissions
This notebook explores a dataset of diabetics' health records at US hospitals between 1998 and 2008. The data is available at https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008.
In the notebook I provide an (lengthy, possibly *too* lengthy) exploratory analysis of the dataset, before going on to evaluate the performance of a few linear ML models against it.

The introduction to the document provides a detailed overview of what's in it:
### Submission overview
#### Load libraries and import data
- Load libraries, import data, check data shape, look for typos, change feature datatypes, encode features, drop features, describe dataset
#### Mining and pre-processing
- Extract independent encounters, encode response, impute for missing values, aggregate diagnoses, remove outliers, one-hot encode categorical features
#### Exploratory data analysis
- Visualise feature correlations with readmission, consider numerical feature correlations, investigate numerical feature distributions according to readmission status, look at diagnosis frequencies, modify dataset in preparation for supervised learning
#### Dimensionality reduction
- Scale dataset, perform PCA, optimise a variance threshold then use it to exclude 'noisy' features, visualise changes in score with variance threshold, visualise explained variance by component
#### Supervised learning
- Discussion of scoring metric, creation of dummy classifier, optimisation of LDA classifier, use of shrinkage on an LR classifier to identify which features to use when training a KNN classifier, model comparision and discussion
#### Unsupervised learning
- K-means clustering with investigation and discussion of cluster meanings, t-SNE dimensionality reduction followed by density-based clustering as a demonstration that it could be used to prepare data for supervised classification
#### Summary
- Review of findings

Suggested extensions/improvements:
  - Other classifiers (SVMs and ensemble methods)
  - Remove waffle
