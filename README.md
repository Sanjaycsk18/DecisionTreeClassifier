# DecisionTreeClassifier

## Overview

   •  Decision Tree is a Supervised learning technique that can be used for both classification and
      Regression problems, but mostly it is preferred for solving Classification problems. 
   
   •  It is a tree-structured classifier, where internal nodes represent the features of a dataset, 
      branches represent  the decision rules and each leaf node represents the outcome.
   
   •  It is a graphical representation for getting all the possible solutions to a problem/decision based 
      on given conditions.
  
## Algorithm 

 **Step-1:** Begin the tree with the root node, says S, which contains the complete dataset.

 **Step-2:** Find the best attribute in the dataset using Attribute Selection Measure (ASM).

 **Step-3:** Divide the S into subsets that contains possible values for the best attributes.

 **Step-4:** Generate the decision tree node, which contains the best attribute.

 **Step-5:** Recursively make new decision trees using the subsets of the dataset created in step -3. Continue this process until a stage is reached where you cannot further classify the nodes and called the final node as a leaf node.

## Working 

 • Feed a dataset, containing a number of training instances, with a set of features and a target

 • Train the decision tree classification or regression models with the help of DecisionTreeClassifier () or DecisionTree 
   Regressor() and add the required criterion while building the decision tree model

 • Use Graphviz to visualize the decision tree model.
 
 ## Example of DecisionTree
 
 ![tree](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQQJXj6KtgabExUFq9ge7N2GaD58xlZuOv-Cg&usqp=CAU)
