# Dimensionality Reduction and Classification on Handwritten Digits Dataset

## Project Overview

This project explores various dimensionality reduction techniques and their impact on classification accuracy across the **Handwritten Digits Dataset**. It involves preprocessing, feature extraction, dimensionality reduction, and classification using conventional and advanced machine learning methods.

## Datasets

### **Handwritten Digits Dataset**
- **Description**: 
  - A subset of handwritten digits (0, 1, 2, 3, 4) with 2066 samples and 784 features.
  - Each feature corresponds to a pixel in a 28x28 grayscale image.


## Objectives

### Handwritten Digits Dataset

1. **Linear Dimensionality Reduction**:
   - Apply **PCA**:
     - Compute eigenvectors and eigenvalues.
     - Create scree plots and scatter plots of top components.
     - Implement PCA and dual PCA manually and compare computation times.
   - Apply **Fisher Discriminant Analysis (FDA)**:
     - Visualize top components and analyze their effectiveness in class separation.

2. **Nonlinear Dimensionality Reduction**:
   - Techniques:
     - Kernel PCA (with RBF kernel)
     - Isomap
     - Locally Linear Embedding (LLE)
     - Laplacian Eigenmap
     - t-SNE
   - Compare embeddings based on their performance in separating classes.

3. **Comparative Analysis**:
   - Evaluate differences between PCA, LDA, and nonlinear methods.
   - Analyze trade-offs in performance, scalability, and interpretability.


## Tools and Technologies

- **Programming Language**: Python
- **Libraries**:
  - **scikit-learn**: Dimensionality reduction, classification, and metrics
  - **matplotlib**, **seaborn**: Data visualization
  - **NumPy**, **Pandas**: Data manipulation and analysis


## Key Results

- PCA and LDA enable dimensionality reduction with minimal loss in classification performance.
- Nonlinear methods like t-SNE and LLE provide superior embeddings for the Handwritten Digits Dataset in terms of visual separation of classes.




