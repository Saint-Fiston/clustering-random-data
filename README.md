# Clustering Assignment – KMeans on Artificial Data
The aim of this assignment is to understand and practically demonstrate clustering on synthetic data using KMeans, while learning how data parameters influence clustering performance and visualization.


## Description
This repository contains my solution for **Practical Assignment 2: Clustering Random Data**, completed as part of my Artificial Intelligence module (CMPG 313).  
The task focuses on generating artificial datasets, applying the **KMeans clustering algorithm**, visualizing results, and evaluating accuracy by comparing clusters to true class labels.

---

## Aim of the Assignment
The aim of this assignment is to:
- Understand the concept of **artificial data generation** for machine learning.  
- Gain hands-on experience with **unsupervised learning** (clustering) using **KMeans**.  
- Learn how dataset parameters (e.g., number of samples, distance between cluster centers, and variance) influence clustering outcomes.  
- Practice **data visualization** using Matplotlib.  
- Compare clustering results with true labels and calculate accuracy.  

---

## Tools & Libraries
- Python 3  
- NumPy  
- Matplotlib  
- scikit-learn  

---

## Steps Implemented
1. **Import Libraries**  
   NumPy, Matplotlib, and scikit-learn’s KMeans.  

2. **Generate Artificial Dataset**  
   - Defined number of samples, distance between cluster centers, and standard deviations.  
   - Added random noise around class centers to create two classes of data points.  

3. **Create Labels**  
   - Assigned `0` for Class 1 and `1` for Class 2.  

4. **Visualize Data**  
   - Plotted the raw dataset to show separation between the two classes.  

5. **Apply KMeans Clustering**  
   - Used `KMeans(n_clusters=2)` to cluster the data.  
   - Obtained cluster labels for each point.  

6. **Align Cluster Labels with True Labels**  
   - Matched predicted clusters to the majority true label within each cluster.  

7. **Evaluate Results**  
   - Calculated **accuracy** of clustering.  
   - Visualized final clustered data.  

---

## Results
- The generated dataset was successfully clustered into **two groups**.  
- After aligning cluster labels with true labels, the clustering achieved a high accuracy (accuracy depends on chosen dataset parameters).  
- Visualizations show how changes in distance (`d`) and variance (`σ`) affect clustering performance.  

---

## Notes
- This is a **school assignment** for CMPG 313.  
- The code and report include full screenshots of implementation and results.  
- The project demonstrates practical understanding of **KMeans clustering** on synthetic data.  

---
