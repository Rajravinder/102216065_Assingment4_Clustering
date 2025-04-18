# 🍷 Clustering Assignment – Wine Dataset

## 📌 Objective
This project performs a comparative analysis of clustering algorithms using various preprocessing techniques and cluster counts, evaluated on multiple metrics.

## 📚 Dataset
**Wine Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine):
- 178 instances
- 13 continuous features (e.g., alcohol, magnesium, flavanoids)
- 3 actual wine classes (used only for evaluation)

## ⚙️ Preprocessing Techniques
- **Raw Data** (no preprocessing)
- **Standardization** (Z-score scaling)
- **Normalization** (Min-Max scaling)
- **PCA** used for 2D visualizations

## 🧠 Clustering Algorithms
- **K-Means**
- **DBSCAN**
- **Agglomerative Clustering**

## 🧪 Evaluation Metrics
- **Silhouette Score** (higher = better)
- **Davies-Bouldin Index** (lower = better)
- **Calinski-Harabasz Index** (higher = better)

## 🔢 Number of Clusters
- Evaluated with 2 to 5 clusters (where applicable)

---

## 📊 Sample Results

| Method        | Algorithm       | Clusters | Silhouette | DB Index | CH Index |
|---------------|------------------|----------|-------------|------------|------------|
| Standardized  | KMeans           | 3        | 0.284       | 0.54       | 183.57     |
| Normalized    | Agglomerative    | 3        | 0.276       | 0.62       | 170.12     |
| Raw           | DBSCAN           | 2        | 0.251       | 0.70       | 150.83     |
| ...           | ...              | ...      | ...         | ...        | ...        |

> 📌 Full result table available in `clustering_results.csv`

---

## 🖼️ Visualizations

2D PCA plots of clusters were generated for each method and cluster count. Examples:

- **K-Means with 3 clusters**  
  ![kmeans](https://via.placeholder.com/400x200.png?text=KMeans+PCA+Plot)

- **Agglomerative with 4 clusters**  
  ![agg](https://via.placeholder.com/400x200.png?text=Agglomerative+PCA+Plot)

- **DBSCAN clustering**  
  ![dbscan](https://via.placeholder.com/400x200.png?text=DBSCAN+PCA+Plot)

---

## ✅ Conclusion

- **Standardization** generally improves clustering performance, especially for K-Means.
- **K-Means** achieved the best scores with 3 clusters, closely matching the ground truth.
- **DBSCAN** struggled due to varying densities.
- **Agglomerative Clustering** also performed well with normalized data.

---

## 💻 How to Run
1. Open the [Colab Notebook](link-to-your-colab) or run it locally.
2. Make sure all required Python libraries are installed.
3. Check `clustering_results.csv` and visualizations for analysis.

---

## 📁 Files
- `clustering_assignment.ipynb` – Main analysis notebook
- `clustering_results.csv` – Result table
- `README.md` – This file

---

## 📬 Contact
Made by **Tuxkun** ✨  
Feel free to fork, clone, and modify!

