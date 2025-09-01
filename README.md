# 📊 DS_Hierarchical_Clustering Project

This project explores regional patterns in case closure outcomes across English local authorities using hierarchical clustering. It uses publicly available data from the Children in Need Census (2013–2024) and aligns with the Children in Need Census 2025–2026 guidance.


## 🔍 Project Objectives
- Cluster local authorities based on closure reasons (e.g. adoption, SGO, transfer to adult services).
- Identify regional patterns and similarities in service outcomes.
- Support benchmarking and policy evaluation using public data.

## 📁 Dataset Summary

This project uses publicly available data from the **Children in Need Census (2013–2024)**, released by the Department for Education under the [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).

### 🔍 Source & Coverage
- **Source**: [Explore Education Statistics Portal](https://explore-education-statistics.service.gov.uk/find-statistics/characteristics-of-children-in-need)
- **Time Period**: 2013 to 2024 (reporting year ends 31 March)
- **Geographic Levels**: National, Regional, Local Authority
- **Topics**: Case closure reasons, referrals, assessments, child protection plans, primary needs, disabilities, ethnicity, and more.

### ⚠️ Data Notes
- Symbols used:
  - `c` = suppressed for confidentiality  
  - `z` = not applicable  
  - `x` = not available  
  - `u` = low reliability  
  - `k` = rounds to zero but not zero  
- Some local authority data is missing:
  - Hackney (2021–2022)
  - Hampshire (2024)
- Rates are calculated per 10,000 children aged 0–17 using ONS mid-year population estimates.


## 🧠 Methodology
1. **Data Cleaning**: Replace non-numeric entries and convert to numeric.
2. **Imputation**: Fill missing values using median.
3. **Feature Scaling**: Apply StandardScaler.
4. **Dimensionality Reduction**: Use PCA (2 components).
5. **Clustering**: Hierarchical clustering with Ward linkage.
6. **Interpretation**: Use CIN guidance to interpret clusters.

## 📁 Folder Structure
DS_Hierarchical_Clustering/ ├── Data/ # Raw and cleaned datasets ├── Notebooks/ # Jupyter notebooks ├── Outputs/ # Visuals, summary tables, final report ├── Docs/ # Guidance and assignment briefs

## 📦 Tools Used
- Python (pandas, numpy, matplotlib, seaborn, sklearn, scipy)
- Jupyter Notebook
- Git & GitHub
- Conda environment


## 📄 Final Report
- Hierarchical Clustering Report

Includes:
- Executive Summary
- Methodology
- Cluster Interpretation
- Data Infrastructure & Tools
- Data Engineering
- Data Visualisation & Dashboards
- Data Analytics
- Recommendations & Conclusion

## 📊 Visuals
- Closure reason distributions (RC1–RC7)
- Correlation heatmap
- Pairplot of closure features
- PCA scatter plot of clusters

## Data Visualisation & Dashboards
The following visuals were created to support interpretation:
1. **Closure Reason Distributions**  
   - RC1 to RC7 distribution plots show how each reason varies across authorities.

2. **🔥 Correlation Heatmap**  
   - Highlights relationships between closure reasons, supporting feature selection.

3. **🧩 Pairplot**  
   - Explores pairwise relationships and clustering potential.


4. **PCA Scatter Plot**  
   - Displays clusters in reduced dimensions for visual separation.


5. **Cluster Interpretation**  
   - Visuals support understanding of regional patterns and cluster characteristics.
     

## 📚 References
- Children in Need Census 2025–2026 Guidance
- M5 Data Science Professional Practice Assessment Brief
- Scikit-learn, SciPy, Matplotlib documentation


## 🔄 Future Work
- Compare clustering methods (K-Means, DBSCAN, GMM)
- Link clusters to outcomes (e.g. re-referrals, CPPs)
- Explore time trends and model drift
- Add interactive dashboards

---

## 🧠 Learning Notes

This repository supports my M5 Data Science Professional Practice assignment. All code is written and reviewed manually to support learning. Outputs are saved locally and versioned via GitHub.

## 🔄 Future Work

- Compare clustering methods (K-Means, DBSCAN, GMM)
- Link clusters to outcomes (e.g. re-referrals, CPPs)
- Explore time trends and model drift
- Add interactive dashboards