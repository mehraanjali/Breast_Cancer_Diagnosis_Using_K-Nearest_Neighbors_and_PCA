# Breast Cancer Diagnosis Using K-Nearest Neighbors (KNN) Classification

## Overview
This project aims to classify breast cancer diagnoses as malignant (M) or benign (B) using the K-Nearest Neighbors (KNN) classification algorithm. It utilizes a dataset containing various features extracted from breast cancer biopsies. The project includes data preprocessing, model training and evaluation, and optional dimensionality reduction using Principal Component Analysis (PCA).

##Description
1. Dataset Import and Exploration
The project begins by importing the Breast Cancer Wisconsin (Diagnostic) dataset, which includes information about the diagnosis and various attributes of cell nuclei in breast cancer biopsies. Attributes include characteristics like 'radius_mean,' 'texture_mean,' 'perimeter_mean,' and more. The dataset is thoroughly explored using summary statistics, histograms, and data type checks.

2. Data Preprocessing
Data preprocessing involves dropping unnecessary columns, separating features (X) from the target variable (y), and splitting the data into training and testing sets. Standardization is applied to the features to ensure consistent scaling for the KNN algorithm.

3. Determining the Optimal Number of Neighbors (K)
The code determines the optimal number of neighbors (K) for the KNN algorithm by testing a range of K values and plotting their corresponding test accuracies. The "elbow point" in the accuracy graph helps select the best K value.

4. Model Training and Evaluation
KNN classification is performed using the selected K value, and the model is trained on the training data. Model accuracy is evaluated on both the training and testing datasets. Additionally, a confusion matrix and classification report are generated to assess the model's performance, including precision, recall, and F1-score.

5. Dimensionality Reduction (Optional)
The code demonstrates an optional step where Principal Component Analysis (PCA) is applied to reduce the dimensionality of the dataset to 2 components. KNN classification is then performed on the reduced dataset, and model accuracy is assessed.

# Interpretation
This project demonstrates the application of the KNN classification algorithm for breast cancer diagnosis. The choice of K and the use of PCA for dimensionality reduction can significantly impact the model's performance. The project provides insights into how the KNN algorithm can be used for medical diagnosis tasks.
