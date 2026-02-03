 Machine Learning Projects 

During my learning journey in Machine Learning, I focused on building a strong foundation by truly understanding the data, the problem, and the behavior of different algorithms — instead of directly jumping into deep learning.

📌 This repository includes multiple machine learning projects covering supervised learning, unsupervised learning, and image-based classification, with one clear goal in mind:  
choosing the simplest effective model for each problem.

---

🔹 1️⃣ Classification on Tabular Data

I worked with real-world demographic and financial data (age, job, education, balance, loans, etc.) to solve a binary classification problem.

- The dataset was highly imbalanced, where the “No” class significantly outnumbered the “Yes” class.
- Data preprocessing included:
  - Removing duplicates and irrelevant features
  - Handling missing values (median for numerical features, mode for categorical features)
  - Treating outliers
  - Feature scaling

- To handle the class imbalance problem, I applied SMOTE, allowing the model to better learn patterns from the minority class.

- Models used:
  - Logistic Regression
  - Decision Tree (with class_weight = balanced)

- Model evaluation was done using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - ROC-AUC

 This project clearly demonstrated why accuracy alone is not a reliable metric when working with imbalanced datasets.

---

 🔹 2️⃣ Clustering (Unsupervised Learning)

To explore the data without labels and understand its structure, I implemented:

- K-Means — to observe centroid-based clustering behavior  
- DBSCAN — to handle noise and detect density-based clusters

This comparison helped highlight how different clustering algorithms respond to:

- Data distribution  
- Noise  
- Cluster density and shape

---

 🔹 3️⃣ Bonus: Image Classification Without Deep Learning

As a bonus project, I worked with the MNIST dataset, intentionally avoiding CNNs or deep learning models.

- Images originally shaped as (28 × 28) were:
  - Flattened into feature vectors (784 features)
  - Normalized from pixel values 0–255 to 0–1 to make them suitable for classical ML models

- A Logistic Regression model was trained as a simple and interpretable baseline for image classification.

The objective here was not achieving state-of-the-art accuracy, but understanding:

- How classical machine learning models handle image data  
- The importance of proper data representation and normalization

---

 Main Takeaway

This work emphasizes that:

- Model selection should always match the nature of the problem  
- Well-prepared data can make simple models very effective  
- Deep learning is powerful, but not always the first or necessary step

All projects are organized and available on GitHub, including preprocessing steps, model comparisons, and evaluation results.

---

 Acknowledgment

I would like to sincerely thank my amazing team for their cooperation, support, and teamwork throughout this work.  
Working with such a collaborative and motivated team made the learning experience more productive and enjoyable.

Truly one of the best teams I’ve had the chance to work with 🤍  
Special thanks to:  

Ziad_Sameh@ZiadSameh-Ai
Merriam_Essam@merriamessam
Mayada_Yasser@mayada258
Rawan_Mohamed@RawanElnaggar
Shereen_Haitham

---

#MachineLearning #DataScience #Classification #Clustering  
#KMeans #DBSCAN #LogisticRegression #DecisionTree  
#MNIST #DataPreprocessing #LearningByDoing
