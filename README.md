# AI-ML-Internship-Task8: K-Means Clustering – Customer Segmentation 🛒📊

## 📖 Description
Day-8 Task of my **AI & ML Internship**: Implementation of **K-Means Clustering** on the Mall Customers dataset for customer segmentation.  
This notebook demonstrates preprocessing, scaling, cluster evaluation, and visualization.

---

## 🚀 Objectives
- Load and preprocess dataset (Mall Customers).  
- Perform **feature scaling** for better clustering.  
- Apply **K-Means algorithm** for segmentation.  
- Determine optimal number of clusters using the **Elbow Method**.  
- Visualize clusters using **PCA (2D projection)**.  
- Evaluate results with **Silhouette Score**.  
- Analyze clusters and draw insights.  

---

## 🛠 Tools & Libraries
- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📂 Repository Contents
AI-ML-Internship-Task8/
│
├── task8.ipynb # Colab notebook with K-Means clustering
├── README.md # Documentation

---

## 📊 Dataset
- **Dataset Used**: [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/datasets/shwetabh123/mall-customers)  
- Features:  
  - `CustomerID`  
  - `Gender`  
  - `Age`  
  - `Annual Income (k$)`  
  - `Spending Score (1–100)`  

---

## 🔎 Implementation Workflow
1. Load dataset & explore features  
2. Feature scaling with `StandardScaler`  
3. Elbow Method to find best K  
4. Apply K-Means clustering  
5. PCA-based 2D visualization  
6. Evaluate with Silhouette Score  
7. Cluster-wise analysis and interpretation  

---

## 📈 Results (Sample)
- Optimal clusters: **K = 5**  
- Silhouette Score: ~0.55  
- Clusters formed based on **Age, Income, Spending Score**  
- Segmentation insights:  
  - High income, high spenders (VIP customers)  
  - High income, low spenders  
  - Low income, high spenders  
  - Young average spenders  
  - Older low spenders  

---

## 📷 Visual Outputs
- Elbow Method Plot  
- PCA 2D Scatter with Cluster Colors  
- Cluster Mean Bar Charts  

*(Add screenshots after running notebook)*  

---

## 🧾 Key Learnings
- K-Means partitions customers into groups with similar behavior.  
- **Elbow Method** helps identify the optimal number of clusters.  
- **Silhouette Score** validates clustering quality.  
- PCA helps visualize high-dimensional clusters in 2D.  
- Customer segmentation is key for **marketing strategies**.  

---

## 👨‍💻 Author
**Balaji**  
B.Tech CSE (AI-ML), Parul University  
