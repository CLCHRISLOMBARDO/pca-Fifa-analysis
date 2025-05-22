# Principal Component Analysis of FIFA Players' Attributes

**Author:** Christian Lombardo  
**Date:** May 10, 2025  
**Course:** Data Mining in Science and Technology  
**Institution:** Facultad de Ciencias Exactas y Naturales, Universidad de Buenos Aires

---

## ⚽ Project Overview

This project applies **Principal Component Analysis (PCA)** to a dataset of professional football players from FIFA to understand the underlying structure of their attributes and reduce dimensionality.

The aim is to identify the most significant axes of variation among players, explore attribute correlations, and provide a visual interpretation of player distributions according to their roles and skills.

---

## 🎯 Objectives

- Standardize and preprocess the dataset of FIFA players.
- Apply PCA to reduce the number of features.
- Analyze the explained variance by each principal component.
- Interpret the loadings and correlations of attributes.
- Visualize players by roles (goalkeepers vs. field players) in PCA space.

---

## 🧪 Methodology

- **Dataset Source:** FIFA player attributes from [Kaggle](https://www.kaggle.com/)
- **Tools:** R
- **Steps:**
  1. Preprocessing (e.g., filtering numeric attributes, removing goalkeepers for field-player PCA)
  2. Standardization of variables
  3. Computation of principal components
  4. Visualization:
     - Scree plot (explained variance)
     - Correlation circle (loadings)
     - Player projection in PC1 vs. PC2 space

---

## 📊 Key Insights

- The first two principal components capture a significant portion of the variance in player skills.
- The projection helps distinguish player types based on attributes such as passing, pace, and defense.
- The correlation circle allows interpretation of how original attributes relate to the new principal axes.

---



