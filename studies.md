# Self-Study Preparation Guide

**⏳ Estimated Prep Time:** 45–60 minutes

Welcome to our flipped-classroom session, where you'll review foundational concepts beforehand to maximize our time for hands-on coding and debugging. This pre-study focuses on **Unsupervised Learning**, a critical domain of machine learning used to discover hidden patterns, segment customers, and detect anomalies in unlabeled data.

By mastering these concepts now, you will be ready to implement and tune clustering algorithms on real-world datasets during our live session.

## ⚡ Your Self-Study Tasks

Please complete the following activities before our session.

### 📝 Task 1: The "What" and "Why" of Anomaly Detection (15 Minutes)

**Activity:** Read the sections titled **"Introduction to Unsupervised Learning"** and **"Outlier and Anomaly Detection"** in the provided `unsupervised_learning_v2.ipynb` notebook. Pay specific attention to the difference between simple "Outliers" and complex "Anomalies".

**Guiding Questions:**

* How might identifying outliers improve the safety of a critical system (e.g., healthcare or fraud detection)?
* Review the **Z-Score** and **Local Outlier Factor (LOF)** methods. How does LOF use "neighbors" to decide if a point is an anomaly compared to the simple statistical approach of a Z-Score?

### 📝 Task 2: Reducing Complexity with Dimensionality Reduction (15 Minutes)

**Activity:** Review the **"Dimensionality Reduction and Manifold Learning"** section. Focus on the visual difference between the raw data and the transformed data using **PCA** (Principal Component Analysis) and **t-SNE**.

**Guiding Questions:**

* Why is it beneficial to reduce high-dimensional data (many columns) into fewer dimensions?
* Look at the **t-SNE** visualization of the MNIST dataset. How does this algorithm group similar items (like handwritten digits) together visually?

### 📝 Task 3: Clustering Strategies (20 Minutes)

**Activity:** Skim the **"Clustering"** section, focusing on the logic flow of **K-Means**, **DBSCAN**, and **Hierarchical Clustering**. Do not worry about running the code yet; focus on how the algorithms make decisions.

**Guiding Questions:**

* **K-Means:** How does the "Elbow Method" (plotting Inertia vs. No. of clusters) help us determine the optimal number of clusters ()?
* **DBSCAN:** Unlike K-Means, DBSCAN has a notion of "noise." How might this be useful for a dataset that is messy or has irregular shapes?
* **Hierarchical:** How does a "Dendrogram" help visualize the relationship between different data points?

## 🙌🏻 Active Engagement Strategies

To deepen your retention, try one of the following while you review:

* **Scenario Matching:** Imagine you are working with retail data. Which algorithm (K-Means, DBSCAN, or Anomaly Detection) would you use to find VIP customers? Which would you use to find credit card fraud?
* **"Code Commentary":** Look at the code block for `KMeans(n_clusters=3)`. Write a brief note explaining what the `model.fit(X)` step is doing conceptually.
* **Concept Mapping:** Sketch a simple comparison table listing the pros and cons of K-Means vs. DBSCAN based on the reading.

## 📖 Additional Reading Material

* [Support Vector Machine (SVM)](https://scikit-learn.org/stable/modules/svm.html)

### 🙋🏻‍♂️ See you in the session!

### Foundation

