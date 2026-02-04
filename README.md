
Machine Learning Projects

This repository contains a collection of machine learning projects that I worked on while learning and practicing core machine learning concepts.  
The focus of these projects is on understanding the data, choosing appropriate algorithms, and building effective models without unnecessary complexity.

Rather than directly using deep learning, these projects emphasize classical machine learning techniques and proper data preprocessing to solve real problems.



 Notebook 1: Binary Classification on Tabular Data

In this project, I worked on a binary classification problem using real-world tabular data that includes demographic and financial features such as age, job, education, balance, loans, and other related attributes.

Problem Description
The target variable represents a binary outcome (Yes / No).  
One of the main challenges in this dataset was class imbalance, where the "No" class significantly outnumbered the "Yes" class.

Data Preprocessing
Several preprocessing steps were applied before training the models:
- Removing duplicate records and irrelevant features
- Handling missing values:
  - Numerical features were filled using the median
  - Categorical features were filled using the mode
- Detecting and treating outliers
- Scaling numerical features to improve model performance

To address the class imbalance issue, SMOTE was applied in order to generate synthetic samples for the minority class and allow the models to better learn its patterns.

 Models Used
- Logistic Regression
- Decision Tree with `class_weight = balanced`

 Evaluation Metrics
Model performance was evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report
- ROC-AUC score

This project demonstrates why accuracy alone is not sufficient when evaluating models trained on imbalanced datasets.



Notebook 2: Clustering (Unsupervised Learning)

This project focuses on exploring the structure of the data without using labels.

Two clustering algorithms were implemented and compared:

 K-Means
K-Means was used to observe centroid-based clustering behavior and how clusters are formed based on distance to centroids.

DBSCAN
DBSCAN was applied to handle noise and identify clusters based on data density rather than predefined cluster counts.

 Key Observations
Through this comparison, it became clear how different clustering algorithms respond to:
- Data distribution
- Noise and outliers
- Cluster density and shape

This helped in understanding when each clustering approach is more appropriate.



 Notebook 3: Bonus – Image Classification Without Deep Learning

As a bonus project, I worked with the MNIST dataset while intentionally avoiding convolutional neural networks or deep learning models.

Data Preparation
- Images with original shape (28 × 28) were flattened into 784-dimensional feature vectors
- Pixel values were normalized from the range 0–255 to 0–1 to make them suitable for classical machine learning algorithms

 Model Used
- Logistic Regression

The goal of this project was not to achieve state-of-the-art accuracy, but to understand how traditional machine learning models can be applied to image data and how data representation and normalization affect performance.



Key Learnings

Through these projects, I learned that:
- Model selection should be driven by the nature of the problem
- Proper data preprocessing can significantly improve model performance
- Simple models can be very effective when used correctly
- Deep learning is powerful, but not always the first or necessary solution



 Repository Structure

Each project includes:
- The dataset (or data loading steps)
- Data preprocessing and feature engineering
- Model training and evaluation
- Clear explanations inside the notebooks



 Acknowledgment

I would like to thank my team members for their cooperation and support throughout these projects.  
Their collaboration and feedback made the learning process more effective and enjoyable.

Special thanks to:
Ziad_Sameh@ZiadSameh-Ai
Merriam_Essam@merriamessam
Mayada_Yasser@mayada258
Rawan_Mohamed@RawanElnaggar
Shereen_Haitham


#MachineLearning #DataScience #Classification #Clustering  
#KMeans #DBSCAN #LogisticRegression #DecisionTree  
#MNIST #DataPreprocessing #LearningByDoing
