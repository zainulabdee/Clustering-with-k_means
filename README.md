 Task 8: Clustering with K-Means  
Dataset: Mall Customer Segmentation  
Objective: Perform unsupervised clustering and evaluate performance.

---

 Overview  
This project demonstrates K-Means Clustering on a customer segmentation dataset. The goal is to group customers into clusters based on their spending behavior using unsupervised learning techniques.

---

 Dataset Details  
- Source: [Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- Features Used:  
  - Annual Income (k$)  
  - Spending Score (1–100)

---

 Tools Used  
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn

---

 Steps Performed  
1. Loaded and explored the dataset  
2. Visualized customer income vs spending score  
3. Applied K-Means Clustering with different values of K  
4. Used the Elbow Method to determine optimal number of clusters  
5. Evaluated clustering using Silhouette Score  
6. Visualized final clusters with color-coded scatter plot

---

 Evaluation  
- Optimal K: Determined using Elbow Method  
- Silhouette Score: Used to evaluate cluster separation  
- Visual Insight: Clustered customers displayed in 2D space

---

 Conclusion  
K-Means successfully grouped mall customers into distinct clusters based on income and spending patterns. The elbow method and silhouette score guided model selection, and visual plots provided clear insights into customer segmentation.
