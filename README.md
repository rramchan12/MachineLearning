# MachineLearning

A set of IPython Notebooks which feed off the following topics 

* Basic_Statistics.ipnb
  - Basic Statistical Calculations using Python 
* PredictiveModels.ipnb
  - Linear, Poly Regresssion, MultiVariate Regression
* SupervisedLearning.ipnb
  - Using Supervised Learning with Poly Regression
* NaiveBayes_SpamClassifier_Using_scikit.pynb
  - Using Naive Bayes to create a Spam Classifier. This doesent use the popular NLTK toolkit for creating features. Rather uses the Sci Kit vectoriser to create the feature Vector. Use in conjunctions with archived emails (warning : small sample size)
* KMeans_using_scikit.ipnb
  - Uses the K Means Algorithm to create a relation between Age and Salary. Totally fudged data, but we start with a known number of centroids. We can see if we change the no, the results turn haywire
 * Decision_Tree_Random_Forests_Graphwiz.ipynb
   - Create classifiers using Decision Trees, and try extending it to Random Forests. Finally use GraphWiz to see a basic visualization
   - Use in conjunction with PastHires.csv
 * predicting_sine_using_decision_tree_with_over_under_fitting.ipynb
    - An example of using a DecisionTreeRegression. We take a sine wave, add some outliers. Then try to predict X given Y. (In DecisionTreeRegression Y is a float). The idea is to show that the tree_depth is an important parameter to avoid overfitting
