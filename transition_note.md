# 

# Clustering Methodology Transition Note

This project initially applied \*\*KMeans clustering\*\* to analyse case closure outcomes across local authorities. KMeans was chosen for its simplicity and scalability, but several challenges emerged:

## Challenges with KMeans

* Data limitations: Required extensive preprocessing due to missing values and categorical variables.
* Cluster shape assumptions: KMeans assumes spherical clusters, which did not reflect the actual data structure.
* Visual limitations: Cluster plots lacked clarity and interpretability.
* Instability: Results varied significantly depending on initialization and cluster count.

## Why Hierarchical Clustering?

* No need to predefine cluster count: Dendrograms allow flexible exploration.
* Handles non-convex clusters: Better for varying shapes and densities.
* Improved visual interpretation: Dendrograms provide clear hierarchical views.
* Robust to noise and missing data: More tolerant of real-world imperfections.

This transition enhances interpretability and supports more nuanced insights for strategic planning.

