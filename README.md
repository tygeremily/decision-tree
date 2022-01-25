# decision-tree
Explore hyperparameter tuning by evaluating decision tree models. 

## Introduction
The purpose of this Python code is to construct decision trees using the Spark ML pipeline.  I implement and evaluate the results of hyperparameter tuning by specifying the range of hyperparameters for the max depth and minimum number of instances per node.  With these hyperparameters I compare and evaluate the decision tree models, using PySpark to perform cross-validation and parameter grid search.  

I originally completed this project using my ICDS-ACI directory that runs the python file along with other files I am unable to include including a decision tree parser, plot, and template.  For this reason I have included a file with images of the resulting graphs for analysis. 

## Technologies 
* Python Version 3.8
* SparkSession

## Libraries/Packages 
* pyspark, pyspark.sql, pyspark.ml
* DecisionTreeClassifier
* OneHotEncoder
* MulticlassClassificationEvaluator
* CrossValidator
* ParamGridBuilder

## Analysis
I have uploaded DTanalysis.pdf that contains images of the best decision trees that were generated and their respective F1 scores.  I have also included a summary/comparison of the F1 scores as well as similarities between the graphs. 
