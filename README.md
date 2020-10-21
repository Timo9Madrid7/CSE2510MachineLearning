# Practical Assignment

In this assignment, you and your teammate will explore different datasets. Each dataset has its own shortcomings and problems that you will have to overcome to find the best possible classifier. During this assignment, you will explore the effectiveness of the following algorithms on these datasets:

• Gaussian Naive Bayes (week 2);

• K Nearest Neighbors (week 3);

• Logistic Regression (week 4);

• Support Vector Machine (week 4);

• Decision Trees (week 6);

For each dataset, we expect you to follow the following structure:

1. Data exploration: In this step, we expect you to explore the properties of the dataset. This includes both the features and the target variables. At the end of this phase, you CSE2510 Delft University of Technology 1 have to decide how hard the problem is and what the right evaluation metric is for this problem.

2. Data preparation: In this step, we expect you to transform the data into the expected format for the algorithm. This step might include some data cleaning, data encoding,
data transformations, etc.
Note: We don’t expect you to do any fancy stuff like outlier handling etc. but it is essential that the data is in the right format and has the right distribution and/or scale.

3. Experiments: In this step, we expect you to do two things. First, you should fit and finetune the algorithms. This step might include hyper-parameter selection, grid search, cross-validation, model evaluation, etc. Secondly, you should evaluate and compare the different models. This step might consist of selecting the right evaluation metrics, visualization, etc.

During this assignment you are allowed to use the Python library Scikit-learn. The beauty of this library is that all its machine learning algorithms follow the same API. You only need to know what the fit, predict and test methods do and you can use every algorithm in the library. To help you get started with this assignment, we have provided you with a template Jupyter Notebook for each dataset. This template takes care of the data loading part and gives you some hints. We have also uploaded an optional Scikit-learn primer notebook to BrightSpace that explains Scikit-learn’s most important methods.
Note: We highly encourage that you use Scikit-learn. If you decided to implement you own version of the algorithms you won’t get any additional points.
