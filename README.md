# Credit-Card-fraud-detection-system-using-Machine-Learning
Detect Fraudulent Credit Card transactions using different Machine Learning models and compare performances

In this notebook, I explore various Machine Learning models to detect fraudulent use of Credit cards. I compare each model performance and results. The best performance is achieved using SMOTE technique.

Please note that this approach can be transferred to other detection analysis in alternatrive domains. The feature extraction process remains similar and can be replicated on many other detection issues.

# Problem Statement
The problem is to develop a machinelearning-based system for real-time credit card fraud detection. The goal is to create a solution that can accurately identify  fraudulent transactions while minimizing false positives. This project involves data preprocessing, feature engineering, model selection, training, and evaluation to create a robust fraud detection systems

# Techniques used in the project
The project compares the results of different techniques :
- Machine learning techniques:
  - Random Forest
  - Decision Trees
- Deep Learning techniques:
  - Neural network using fully connected layers.
 
  - Performance of the neural network is compared for different optimization approaches:
- plain binary cross-entropy loss minimization
- minimization using weights to compensate for the class imbalance
- Under-sampling of the non-fraudulent class to match the fraudulent class
- Over-sampling of the fraudulent class to match the non-fraudulent one by implementing SMOTE technique. The SMOTE method allows to generate a new vector using 2 existing datapoints. For additional details on this approach, you can read this detailed post [SMOTE for Imbalanced Classification with Python]

Note about the difference between Random Forest and Decision tree models:
- A Random Forest is essentially a collection of Decision Trees. A decision tree is built on an entire dataset, using all the features/variables, whereas a random forest randomly selects observations (rows) and specific features/variables to build multiple decision trees from and then averages the results. After a large number of trees are built using this method, each tree "votes" or chooses the class, and the class receiving the most votes by a simple majority is the "winner" or predicted class. 
 
















