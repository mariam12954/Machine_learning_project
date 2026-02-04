# Machine Learning Projects

This repository contains a collection of machine learning projects completed by the team to strengthen practical understanding of core ML concepts.  
The focus of these projects was on understanding the data, selecting appropriate algorithms, and building effective models without unnecessary complexity.

Instead of directly using deep learning, the projects emphasize classical machine learning techniques and proper data preprocessing to solve real-world problems.

---

## Notebook 1: Binary Classification on Tabular Data

The team worked on a binary classification problem using real-world supervised data containing financial and survey-based features such as age, job, education, balance, and loan status.

**Problem Description**  
The target variable represents a binary outcome (Yes / No).  
One of the main challenges was class imbalance, where the "No" class significantly outnumbered the "Yes" class.

**Data Preprocessing**  
Several preprocessing steps were applied:
- Removing duplicate records and irrelevant features  
- Handling missing values:
  - Numerical features filled using the median  
  - Categorical features filled using the mode  
- Detecting and treating outliers  
- Scaling numerical features to improve model performance  

SMOTE was applied to handle class imbalance, allowing models to better learn patterns from the minority class.

**Models Used**
- Logistic Regression  
- Decision Tree (with `class_weight = balanced`)

**Evaluation Metrics**
- Accuracy  
- Confusion Matrix  
- Classification Report  
- ROC-AUC score  

This notebook highlights why relying solely on accuracy is insufficient when evaluating models trained on imbalanced datasets.

---

## Notebook 2: Clustering (Unsupervised Learning)

The team explored the structure of the data without using labels by implementing two clustering algorithms:

- **K-Means:** to observe centroid-based clustering behavior and cluster formation  
- **DBSCAN:** to handle noise and detect density-based clusters  

**Key Observations**  
The comparison revealed how clustering algorithms respond differently to data distribution, noise, and cluster density, and helped identify when each approach is most appropriate.

---

## Notebook 3: Bonus – Image Classification Without Deep Learning

As an additional experiment, the team worked with the MNIST dataset while intentionally avoiding convolutional neural networks or deep learning models.

**Data Preparation**
- Images (28 × 28) were flattened into 784-dimensional feature vectors  
- Pixel values were normalized from 0–255 to 0–1 for compatibility with classical ML models  

**Model Used**
- Logistic Regression  

The focus was on interpretability and understanding how classical machine learning models handle image data, rather than achieving the highest possible accuracy.

---

## Key Learnings

The team concluded that:
- Model selection should be driven by the nature of the problem  
- Proper data preprocessing significantly improves model performance  
- Simple models can be highly effective when used correctly  
- Deep learning is powerful, but not always the first or necessary solution  

---

## Repository Structure

Each notebook includes:
- The dataset (or steps to load the data)  
- Data preprocessing and feature engineering  
- Model training and evaluation  
- Explanations and notes embedded in the notebook  

---

## Acknowledgment

Special thanks to the team members for their cooperation and support throughout these projects.  
Their collaboration and feedback made the learning experience productive and enjoyable.

Team members:  
Ziad_Sameh@ZiadSameh-Ai  
Merriam_Essam@merriamessam  
Mayada_Yasser@mayada258  
Rawan_Mohamed@RawanElnaggar  
Shereen_Haitham  

---

#MachineLearning #DataScience #Classification #Clustering  
#KMeans #DBSCAN #LogisticRegression #DecisionTree  
#MNIST #DataPreprocessing #LearningByDoing
