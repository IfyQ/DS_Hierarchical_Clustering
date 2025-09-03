# DS_Hierarchical_Clustering

## 📌 Project Overview
This project applies hierarchical clustering to group local authorities in England based on case closure reasons from the Children in Need Census (2013–2024). It supports benchmarking, policy evaluation, and strategic planning.

As a practitioner in social services, with a focus on children and adult services, I selected this dataset due to its relevance to my domain and its potential to inform evidence-based decision-making.

## 🧰 Tools & Environment
- **Python (Jupyter Notebook)**: Interactive development and analysis.
- **Pandas & NumPy**: Data manipulation and transformation.
- **Scikit-learn**: Feature scaling and PCA.
- **SciPy**: Hierarchical clustering (Ward linkage, dendrogram).
- **Matplotlib & Seaborn**: Visualisation.
- **Git & GitHub**: Version control and portfolio hosting.
- **Conda Environment**: Ensures reproducibility.

## 🔄 Methodological Transition
Originally implemented using KMeans clustering, the project transitioned to hierarchical clustering due to:
- Poor visual clarity and interpretability.
- Instability in cluster assignment.
- Limitations in handling non-spherical clusters.

📄 Read the full transition note

Hierarchical clustering was chosen for its:
- Flexibility in cluster number selection.
- Stability and reproducibility.
- Clear visual outputs (dendrograms, PCA plots).

## 🛠️ Data Engineering
- Cleaned non-numeric entries (e.g., 'c', 'z', 'x')
- Imputed missing values using median
- Scaled features using StandardScaler
- Merged reference data for interpretation
- Applied PCA for dimensionality reduction

## 📊 Visualisations
- Dendrogram of hierarchical clusters
- PCA scatter plot with cluster labels
- Cluster distribution by region
- Closure reason boxplots and heatmaps

## 📈 Analytics
- Ward linkage method used for clustering
- Distance threshold = 20
- 11 clusters identified
- Cluster interpretation aligned with CIN guidance

## 📁 Outputs
- `dendrogram.png`
- `pca_scatter.png`
- `cluster_region_bar.png`
- `cluster_summary.csv`

## 📚 References
- Children in Need Census Guidance (DfE, 2024)
- Scikit-learn & SciPy documentation
- Gupta et al. (2023) – Clustering comparison

---
