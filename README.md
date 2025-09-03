# DS_Hierarchical_Clustering

## 📌 Project Overview
This project applies hierarchical clustering to group local authorities in England based on case closure reasons from the Children in Need Census (2013–2024). It supports benchmarking, policy evaluation, and strategic planning.

As a practitioner in social services, with a focus on children and adult services, I selected this dataset due to its relevance to my domain and its potential to inform evidence-based decision-making in my organisation.

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
- Replaced non-numeric entries ('c', 'z', 'x', 'u', 'k') with NaN
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

- DataCamp (2025) Hierarchical clustering: concept overview with examples. Available at: https://www.datacamp.com/tutorial/hierarchical-clustering (Accessed: 2 September 2025).

- Department for Education (2024) Characteristics of children in need in England. Available at: https://explore-education-statistics.service.gov.uk/find-statistics/characteristics-of-children-in-need (Accessed: 2 September 2025).

- Department for Education (2024) Children in Need Census 2024 to 2025: Guide. Available at: https://www.gov.uk/government/publications/children-in-need-census-2024-to-2025-guide (Accessed: 2 September 2025).

- Gupta, A., Sharma, H. and Akhtar, A. (2023) ‘A comparative analysis of K-means and hierarchical clustering’, EPRA International Journal of Multidisciplinary Research. Available at: https://eprajournals.com/IJMR/article/5796/download (Accessed: 2 September 2025).

- Larose, D.T. and Larose, C.D. (2014) Discovering knowledge in data: An introduction to data mining. 2nd edn. Wiley. Available at: https://ieeexplore.ieee.org/book/10066951 (Accessed: 2 September 2025).

- Microsoft (2025) Copilot (GPT-4) [Large Language Model]. Available at: https://copilot.microsoft.com (Accessed: 2 September 2025).

- Pedregosa, F. et al. (2011) ‘Scikit-learn: Machine learning in Python’, Journal of Machine Learning Research, 12(Oct), pp. 2825–2830.

- The National Archives (2015) Open Government Licence v3.0. Available at: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/ (Accessed: 2 September 2025).

- Virtanen, P. et al. (2020) ‘SciPy 1.0: Fundamental Algorithms for Scientific Computing in Python’, Nature Methods, 17(3), pp. 261–272.

---
