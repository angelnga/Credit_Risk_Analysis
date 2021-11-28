# Credit_Risk_Analysis
Supervised Machine Learning

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.<br>

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.<br>

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. <br>

## Project Overview
- Deliverable 1: Use Resampling Models to Predict Credit Risk
  1. Naive Random Oversampling: <br>
  ![Naive Random Oversampling](/Image/Naive_Random_Oversampling.png)
  3. Synthetic Minority Oversampling Technique (SMOTE): <br>
  ![SMOTE Oversampling¶](/Image/SMOTE_Oversampling.png)
  4. ClusterCentroids (Undersampling): <br>
  ![Undersampling](/Image/Undersampling.png)
- Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
  - SMOTEENN Sampling: <br>
  ![SMOTEENN Sampling](/Image/SMOTEENN_CombinationSampling.png)
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
