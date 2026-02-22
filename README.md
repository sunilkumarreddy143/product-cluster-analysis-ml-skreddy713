# 🧠 Product Cluster Analysis using KMeans, Hierarchical & DBSCAN

## 📌 Project Overview
This project focuses on segmenting products based on sales and transactional attributes using unsupervised machine learning techniques.

Clustering helps in identifying hidden patterns within the dataset and grouping similar products together to extract meaningful business insights.

---

## 🎯 Objective
- Perform data preprocessing and scaling
- Apply multiple clustering algorithms
- Compare clustering techniques
- Identify optimal number of clusters
- Derive business insights from clusters

---

## 📊 Dataset Description
The dataset contains product-level sales information including:

- Calendar Year
- Month
- Supplier
- Item Code
- Item Description
- Item Type
- Retail Sales
- Retail Transfers
- Warehouse Sales

These variables were used to identify meaningful product segments.

---

## ⚙️ Preprocessing Steps
- Data cleaning
- Handling categorical variables
- Feature scaling using StandardScaler
- Dimensionality preparation for clustering

---

## 🧠 Clustering Algorithms Implemented

### 1️⃣ KMeans Clustering
- Used Elbow Method to determine optimal number of clusters
- Evaluated using Silhouette Score
- Provided well-separated clusters

### 2️⃣ Hierarchical Clustering
- Used Agglomerative approach
- Dendrogram analysis performed
- Compared cluster compactness with KMeans

### 3️⃣ DBSCAN
- Density-based clustering
- Identified noise points
- Effective in detecting outliers

---

## 📊 Cluster Evaluation
Evaluation techniques used:
- Elbow Method
- Silhouette Score
- Visual cluster inspection
- Algorithm comparison

---

## 📈 Business Insights
- Identified high-performing product groups
- Segmented products based on sales behavior
- Detected potential low-performing or seasonal clusters
- Identified outliers using DBSCAN

These insights can support inventory management, supplier analysis, and business strategy decisions.

---

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Seaborn

---

## 📂 Project Structure
```
product-cluster-analysis-ml/
│
├── notebooks/
│ ├── product_cluster_analysis_preprocessing.ipynb
│ └── product_cluster_analysis_code.ipynb
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

---

## 🚀 Key Highlights
✔ Multiple clustering algorithm comparison  
✔ Proper scaling before clustering  
✔ Business-focused interpretation  
✔ Outlier detection using DBSCAN  
✔ Unsupervised learning implementation  

---

## 📌 Conclusion
KMeans provided structured and interpretable clusters, while Hierarchical clustering offered comparative insights into cluster formation. DBSCAN was useful for identifying noise and density-based groupings.

This project demonstrates practical implementation of unsupervised machine learning for business segmentation.

---

### 👨‍💻 Author
Sunil Kumar Reddy
