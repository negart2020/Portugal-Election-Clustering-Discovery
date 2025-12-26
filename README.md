# 🔍 Discovering Political Patterns: Unsupervised Learning on Portugal Elections

This project explores the 2019 Portugal Election results through the lens of Unsupervised Learning. Instead of predicting outcomes, it focuses on identifying hidden similarities between electoral districts and reducing data complexity.

### 📅 Project Context
- **Developed**: Summer 2024 (Mordad 1403)
- **Dataset**: Portugal Real-time Election Results (2019)
- **Objective**: Uncovering latent voting structures and regional clusters.

### 🧠 Key Machine Learning Techniques
- **PCA (Principal Component Analysis)**: Reduced the high-dimensional political dataset (with numerous parties and regions) into 2D space to visualize how districts relate to each other.
- **DBSCAN Clustering**: Used density-based clustering to find natural groups of voters and, more importantly, to detect **outliers** (districts with unique/unusual voting behaviors).
- **K-Means**: Performed as a secondary clustering method to compare with DBSCAN results.

### 🛠 Tech Stack
- **Python** (Scikit-learn, Pandas, NumPy)
- **Visualization**: Matplotlib & Seaborn for PCA scatter plots and cluster distribution.

### 🖼 Visualization Preview
<img width="790" height="590" alt="image" src="https://github.com/user-attachments/assets/4612ced5-6ac4-440d-885c-eccc14cf094a" />
<img width="790" height="590" alt="image" src="https://github.com/user-attachments/assets/e5688a3d-ee94-4151-9627-65a5f30a1cd1" />
<img width="790" height="590" alt="image" src="https://github.com/user-attachments/assets/2d0b809e-9bc3-4d92-ae23-5edfe8ae01e7" />
<img width="790" height="590" alt="image" src="https://github.com/user-attachments/assets/7b807ec6-f55d-4cfc-bafa-48420c68f28c" />
<img width="942" height="790" alt="image" src="https://github.com/user-attachments/assets/eb11b0e6-819d-4eed-9008-ec546499c757" />

Note: For the predictive (Supervised) modeling of this dataset, check out my other repository: https://github.com/negart2020/Portugal-Election-Results-Prediction
