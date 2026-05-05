# 🛍 Customer Segmentation using K-Means Clustering

This project focuses on grouping customers into meaningful clusters based on their spending behavior and income patterns using unsupervised machine learning.

It helps businesses understand customer behavior and improve targeted marketing strategies.

## 📂 Dataset

The dataset used in this project was taken from **Kaggle**.

Features include:

* CustomerID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1-100)

Important features used for clustering:

* Age
* Annual Income
* Spending Score
* Gender

## 🧠 Techniques Used

This project uses unsupervised learning techniques:

* K-Means Clustering
* Elbow Method
* Silhouette Score

The optimal number of clusters was selected after experimentation.

## 📊 Output

The model groups customers into clusters such as:

* High income, high spending customers
* High income, low spending customers
* Low income, high spending customers
* Low income, low spending customers

Cluster visualization was performed using scatter plots.

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
