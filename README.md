# 5G-Architectures-Technologies-Applications-And-Key-Efficiency-Indexes

# 📡 Internet Activity Clustering Project

This project aims to uncover hidden behavioral patterns in **internet activity data** using **unsupervised clustering techniques**. It explores how different regions or users behave across time based on telecommunications usage data.

## 📊 Dataset Description

The dataset contains aggregated features across geographic grid regions, including:

- Hourly internet usage  
- SMS and call frequency  
- Peak activity times  
- Weekday vs. weekend behavior  
- Time-based metrics such as minimum/maximum values by hour  

## 🧠 Methodology

We apply and compare the following unsupervised learning algorithms:

- **K-Means**
- **DBSCAN**
- **Hierarchical Clustering**

In addition, we perform:

- **Feature selection** to focus on the most informative dimensions  
- **PCA (Principal Component Analysis)** to reduce dimensionality and improve visualization  
- **Silhouette analysis** to evaluate cluster separation

## 🗺️ Visualization

Clusters are visualized spatially using `GeoPandas` to highlight:

- Usage hotspots  
- Low-activity or rural zones  
- Noise points and outliers (e.g., from DBSCAN)  
- Behavioral segmentation across different times of day or week

## 🎯 Objectives

- Discover interpretable behavioral clusters  
- Support **network optimization** for telecom providers  
- Enable **targeted service planning**  
- Improve **user segmentation and profiling**

## 🧰 Tools & Libraries

- Python 3.x  
- `scikit-learn`, `pandas`, `numpy`, `matplotlib`  
- `GeoPandas`, `Shapely`  
- `scipy` for hierarchical clustering  
- `KneeLocator` for elbow detection (optional)

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/internet-activity-clustering.git
   cd internet-activity-clustering


![Στιγμιότυπο οθόνης 2025-04-05 015729](https://github.com/user-attachments/assets/f52f0b7f-36ab-4c98-b377-385358dcce90)

