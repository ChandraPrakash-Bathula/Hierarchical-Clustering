# Hierarchical Clustering : Wine Clustering Analysis 🍇

This project demonstrates an exploratory analysis and clustering of wine data using Agglomerative Clustering, a hierarchical clustering technique. It employs the wine dataset, focusing on uncovering inherent groupings based on wine characteristics such as Alcohol, Malic Acid, and Ash content. Visualizations include dendrograms for understanding cluster formations and scatter plots for visual inspection of clusters in both 2D and 3D.

## 🚀 Getting Started

To run this analysis, ensure you have Python installed on your system along with the necessary libraries: Pandas, NumPy, Matplotlib, SciPy, Seaborn, and scikit-learn.

### Prerequisites

- Python 🐍
- Pandas 📊
- NumPy 🔢
- Matplotlib 📉
- SciPy 🔬
- Seaborn 🎨
- scikit-learn 🤖

### Installation

First, clone the repository or download the analysis script. Then, install the required Python packages using pip:

```bash
pip install pandas numpy matplotlib scipy seaborn scikit-learn
```

### Dataset

The analysis is performed on a "wine-clustering.csv" file, which should be placed in the same directory as the script. This dataset must have several features related to wine characteristics, with the first column being an identifier and the subsequent columns representing different attributes.

## 📊 Analysis Overview

The script follows these steps to analyze the wine data:

1. **Data Loading**: Reads the wine dataset into a Pandas DataFrame.
2. **Feature Extraction**: Selects the relevant features for clustering.
3. **Agglomerative Clustering**: Applies Agglomerative Clustering to categorize wines into clusters based on their features.
4. **Dendrogram Visualization**: Generates a dendrogram to visualize the hierarchical clustering structure.
5. **Cluster Visualization**: Plots the clusters in both 2D and 3D to inspect the distribution of wine samples.
6. **Box and Violin Plots**: Creates box and violin plots to compare the distribution of key features across different clusters.

## 🏃‍♂️ Running the Analysis

To perform the analysis, navigate to the directory containing the script and dataset, then execute the script:

```bash
python wine_clustering_analysis.py
```

## 📈 Results

The script will output:

- Cluster labels for each wine sample.
- A dendrogram 🌳 to visualize the clustering hierarchy.
- 2D and 3D scatter plots showing the clusters based on selected features.
- Box 📦 and violin 🎻 plots to compare feature distributions across clusters.

## 📝 Conclusion

This analysis provides insights into the natural groupings within the wine dataset based on selected chemical properties. It showcases the power of hierarchical clustering in understanding complex datasets and lays the groundwork for further exploration, such as identifying characteristics that define premium wines or tailoring wine recommendations.

---
