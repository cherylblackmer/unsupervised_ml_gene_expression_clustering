#Unsupervised Machine Learning Final Project - RNA-Seq (HiSeq) PANCAN Dataset

Introduction: 

The goal of this project is to analyze RNA-Seq (HiSeq) data using clustering methods from the PANCAN dataset, which includes gene expression data from patients with various types of tumors such as Breast Invasive Carcinoma (BRCA), Kidney Renal Clear Cell Carcinoma (KIRC), Colon Adenocarcinoma (COAD), Lung Adenocarcinoma (LUAD), and Prostate Adenocarcinoma (PRAD). This dataset offers an ideal resource for analyzing molecular mechanisms in cancer, an increasingly large problem. By applying unsupervised machine learning techniques to this high-dimensional data (initially excluding the data labels), hidden patterns and structures can be uncovered. Dimensionality reduction methods like Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE), combined with clustering algorithms such as K-means and hierarchical clustering, can reveal distinct biological states or conditions. This analysis not only provides insights into gene expression profiles but also demonstrates the potential of unsupervised learning in advancing personalized medicine and biomarker discovery. The application of these techniques to RNA-Seq data has revolutionized the understanding of cancer biology and holds promise for improving academic and real-world medical research applications.

Dataset: The Cancer Genome Atlas Pan-Cancer Analysis Project. RNA-Seq (HiSeq) PANCAN Dataset. Synapse ID: syn4301332. Available at: https://www.synapse.org/#!Synapse:syn4301332

Note: This dataset was also used for a class assignment, but a unique approach was taken in each portion of the project. Analysis, data cleaning, and model implementation were done completely from scratch.

Project Structure:

1. Data Loading and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Dimensionality Reduction
4. Clustering Analysis
5. Evaluation of Clustering Performance
6. Discussion and Conclusion

Dicussion/Conclusion:

The analysis of gene expression data using principal component analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE) reveals compelling clustering patterns, suggesting the presence of distinct biological states or conditions within the dataset. PCA visualization demonstrates several dense clusters along its first two principal components, which account for a substantial portion of the data's variance. The cumulative explained variance plot exhibits a pronounced elbow around 100 components, indicating that these components capture the most critical aspects of the data. This finding potentially allows for dimensionality reduction while preserving essential information, simplifying subsequent analyses. t-SNE visualization complements the PCA results by uncovering clusters that are less apparent in the PCA plot. This showcases t-SNE's strength in handling complex, non-linear relationships among high-dimensional data points, providing additional insights into the dataset's structure. The combination of these two techniques offers a more comprehensive view of the underlying patterns in the gene expression data.

In terms of clustering performance, both K-means and hierarchical clustering algorithms demonstrate high effectiveness in grouping the data. This is reflected in the impressive scores for metrics such as the Adjusted Rand Index (ARI) and Normalized Mutual Information (NMI). These metrics indicate strong concordance between the clusters formed by these unsupervised methods and the true labels, suggesting that the clustering results have practical biological relevance. The similarity in performance between K-means and hierarchical methods provides flexibility in selecting an algorithm based on specific analytical requirements, such as scalability for large datasets or interpretability of results. This analysis not only supports the hypothesis that gene expression levels can be effectively clustered to uncover patterns but also underscores the potential of unsupervised learning techniques in revealing hidden structures within complex biological data. The insights gained from this approach could guide more targeted scientific inquiries, potentially leading to the development of novel therapeutic strategies. Furthermore, the robust performance of these clustering methods on gene expression data demonstrates their value as tools for exploring and understanding the intricate relationships within biological systems, spurringadvancements in personalized medicine and biomarker discovery.
