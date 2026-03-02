#  Hybrid Retail Customer Segmentation & Strategy

An end-to-end customer segmentation project combining multiple clustering techniques with business strategy development.

This project identifies actionable retail customer segments using both traditional and advanced machine learning methods and translates them into targeted marketing strategies.


##  Project Overview

Retail businesses generate large volumes of customer data but often lack structured segmentation strategies.

This project applies:

- K-Means Clustering
- DBSCAN (Density-Based Clustering)
- Gaussian Mixture Models (Probabilistic Clustering)
- Self-Organizing Maps (SOM)
- PCA, t-SNE, and UMAP for visual validation

The objective is to build robust, interpretable customer segments and align them with clear business strategies.


##  Methodology

### 1 Data Preprocessing
- Feature selection (behavioral + product preference)
- Standardization and scaling
- Outlier detection using DBSCAN

### 2 Clustering Approaches
- K-Means (baseline segmentation)
- Gaussian Mixture Models (confidence-based clustering)
- K-Means (topology-preserving segmentation)

### 3 Visual Validation
- PCA (global structure)
- t-SNE (local structure)


### 4 Business Profiling
- Cluster interpretation using standardized feature means
- Segment naming and persona creation
- Strategic marketing recommendations


### Final Customer Segments

| Cluster | Segment Name | Strategic Focus |
|----------|------------------------------|-------------------------------|
| 0 | Affluent Digital Spenders | Digital optimization |
| 1 | Premium Frequent Shoppers | Increase basket size |
| 2 | Value-Oriented Appliance Buyers | Discount campaigns |
| 3 | Offline Home-Focused Families | In-store promotions |
| 4 | Mid-Income Home Buyers | Cross-selling |
| 5 | Fashion-Oriented Mid Spenders | Trend campaigns |
| 6 | Luxury Omnichannel VIPs | Premium retention |


##  Business Impact

This segmentation enables:

- Targeted marketing campaigns  
- Customer lifetime value optimization  
- Upselling and cross-selling strategies  
- Channel-specific personalization  
- Loyalty tier development  

The project bridges advanced clustering techniques with actionable business insights.


##  Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- MiniSom
- Seaborn / Matplotlib


##  Project Structure

```
01_data_preprocessing.ipynb
02_clustering_segmentation.ipynb
03_density_probabilistic_methods.ipynb
04_som_topology_analysis.ipynb
05_visual_validation_pca_tsne_umap.ipynb
06_business_profiling_strategy.ipynb
```

---

##  Key Learnings

- Comparing deterministic vs probabilistic clustering
- Understanding density-based noise detection
- Using topology-preserving Self-Organizing Maps
- Validating segmentation through dimensionality reduction
- Translating clustering outputs into marketing strategies

---


##  Author

Sapana Dhami


---

 If you found this project interesting, feel free to connect!