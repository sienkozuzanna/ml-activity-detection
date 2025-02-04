# Advanced Feature Engineering and Model Evaluation for Movement Classification
# Authors:
- Hubert Sobociński
- Zuzanna Sieńko
## Overview

This repository contains a comprehensive suite of Jupyter Notebooks dedicated to the in-depth exploration of exploratory data analysis (EDA), advanced feature engineering, and machine learning model evaluation for movement classification using multi-sensor data. The primary objective is to systematically assess the discriminative power of kinematic features, such as velocity and acceleration, in distinguishing between motion modalities. This study incorporates sophisticated methodologies for feature extraction, dimensionality reduction, and supervised classification.

## Key Components

### 1. Exploratory Data Analysis (EDA)

⏳ Temporal Feature Analysis: Includes precise time synchronization and drift correction methodologies.

🔄 Orientation Analysis: Comprehensive quaternion representation (qz, qy, qx, qw) and Euler transformations (roll, pitch, yaw) to ensure robust handling of rotational data.

📍 Geospatial Data Evaluation: Latitude, longitude, altitude, and bearing estimations with uncertainty quantification.

🎯 Accuracy Assessment: Evaluation of location and velocity measurement reliability with probabilistic confidence intervals.

📊 Visualization & Statistical Insights: Advanced statistical and graphical representations to elucidate movement patterns and sensor noise characteristics.

### 2. Feature Engineering

⚙️ High-Order Feature Generation: Includes jerk, curvature, and instantaneous heading changes.

🔧 Data Processing: Implementation of normalization, outlier handling, and feature scaling strategies to improve model generalization.

### 3. Dimensionality Reduction

📉 Principal Component Analysis (PCA): Orthogonal decomposition of feature space to optimize variance preservation.

🔍 t-Distributed Stochastic Neighbor Embedding (t-SNE): Nonlinear manifold visualization for enhanced interpretability.

📡 Device-Specific PCA: Addresses sensor heterogeneity and domain adaptation challenges.

### 4. Model Training & Evaluation

🤖 Classification Algorithms: Deployment of multiple paradigms, including ensemble learning (Random Forest, Gradient Boosting) and neural networks.

📊 Performance Metrics: Comparative evaluation using precision-recall curves, area under the ROC curve (AUC-ROC), and Matthews correlation coefficient (MCC).

🔍 Hyperparameter Optimization: Fine-tuning through grid search and Bayesian optimization techniques to maximize predictive efficacy.

## Results and Insights

📌 Variability in Raw Sensor Data: Initial data exploration revealed significant variability, necessitating feature engineering.

🚀 Impact of Feature Engineering: Augmented feature sets substantially improved model robustness and predictive performance.

🎭 Dimensionality Reduction Insights: PCA and t-SNE provided crucial insights into the intrinsic structure of motion data but were insufficient standalone classification tools.

🏆 Model Selection & Optimization: Rigorous cross-validation identified the optimal classification models, emphasizing the necessity of hyperparameter tuning.

