# Sampling

# Sampling Techniques
1. Simple Random Sampling:
  
   A straightforward random selection of data points.
2. Stratified Random Sampling:

   Ensures proportional representation of classes in both training and testing sets.
3. Systematic Random Sampling:

   Selects data points at fixed intervals.
4. Cluster Sampling:

   Involves grouping data into clusters and randomly selecting entire clusters.
5. Bootstrap Sampling:

    Randomly samples with replacement, allowing for the generation of multiple datasets.

# Models Used
1. Logistic Regression

   A linear model suitable for binary classification tasks, widely used for its simplicity and interpretability.
2. Random Forest

   An ensemble learning method that builds a multitude of decision trees to improve accuracy and control overfitting.
3. K-Nearest Neighbors

   A non-parametric method used for classification based on the majority class among its k-nearest neighbors.
4. XGBoost Classifier

   An efficient and scalable gradient boosting algorithm known for its speed and performance in structured/tabular data.
5. Support Vector Classifier

   A supervised learning algorithm that analyzes data and recognizes patterns, commonly used for classification tasks.

# Results
The performance of each model is evaluated under different sampling techniques. 
1. Logistic Regression:

   Highest Accuracy: Achieved with Bootstrap Sampling.

2. Random Forest:
   
   Highest Accuracy: Achieved with Bootstrap Sampling.

3. K-Nearest Neighbors (KNN):
  
   Highest Accuracy: Achieved with Cluster Sampling.

4. XGBoost Classifier:
  
   Highest Accuracy: Achieved with Stratified Random Sampling.

5. Support Vector Classifier (SVC):
  
   Highest Accuracy: Achieved with Stratified Random Sampling.
