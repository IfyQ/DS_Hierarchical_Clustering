# Clustering Methodology Transition Note

I initially applied **KMeans clustering** to analyze case closure outcomes across local authorities. This method was selected for its simplicity and scalability. However, several challenges emerged:

## Challenges with KMeans
- **Data limitations**: Required extensive preprocessing due to missing values and categorical variables.
- **Cluster shape assumptions**: KMeans assumes spherical clusters, which did not reflect the actual data structure.
- **Visual limitations**: Cluster plots lacked clarity and interpretability.
- **Instability**: Results varied significantly depending on initialization and cluster count.

## Why Hierarchical Clustering?
- **No need to predefine cluster count**: Dendrograms allow flexible exploration.
- **Handles non-convex clusters**: Better for varying shapes and densities.
- **Improved visual interpretation**: Dendrograms provide clear hierarchical views.
- **Robust to noise and missing data**: More tolerant of real-world imperfections.

This transition enhances interpretability and supports more nuanced insights for strategic planning.