# 🚗 Unsupervised Learning Project – Car Clustering & Vehicle Classification

## 📌 Project Overview

This project is divided into **two main parts**, each applying unsupervised and supervised learning techniques to solve real-world automotive problems. It involves clustering cars using K-Means and applying dimensionality reduction (PCA) followed by classification using Support Vector Machines (SVM).

---

## 🧩 Part A: Car Segmentation using K-Means Clustering

### 🚘 Domain: Automobile (Fuel Efficiency)

### 📊 Datasets:
- `Car name.csv` – Car model names
- `Car-Attributes.json` – Attributes such as MPG, cylinders, horsepower, weight, displacement, etc.

### 🧠 Objective:
Understand and implement **K-Means clustering** to group similar cars based on performance and technical features.

### 🛠️ Key Steps:
- Merged car name and attributes datasets
- Handled missing values (e.g., '?' in horsepower), and duplicates
- Conducted EDA:
  - Pairplots
  - Scatterplots with categorical color separation
  - 5-point summary
- Applied K-Means for `k=2` to `k=10`
- Visualized the elbow curve to find optimal `k`
- Labeled data with cluster assignments
- Predicted the cluster of new data points

### 📌 Outcome:
Segmented cars into meaningful clusters based on multivariate attributes, enabling insights into fuel efficiency and design groupings.

---

## 🚙 Part B: Vehicle Classification using PCA & SVM

### 🛻 Domain: Automobile (Silhouette Recognition)

### 📊 Dataset:
- `vehicle.csv` – Contains numeric features extracted from silhouettes of 4 vehicle types (bus, van, and two cars)

### 🧠 Objective:
Use **Principal Component Analysis (PCA)** to reduce feature dimensions and train an SVM model for vehicle type classification.

### 🛠️ Key Steps:
- Cleaned and standardized the dataset
- Visualized class distribution and identified duplicates
- Trained a baseline **SVM classifier** and evaluated its performance
- Applied PCA:
  - Visualized cumulative explained variance
  - Selected components to retain ≥90% variance
- Re-trained SVM with PCA-transformed features
- Tuned hyperparameters to improve classification performance
- Compared results before and after dimensionality reduction

### 📌 Outcome:
Improved classification performance through dimensionality reduction, showing that PCA can reduce complexity while preserving accuracy.

---

## ⚙️ Tools, Libraries & Skills Used

- **Programming:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Seaborn, Matplotlib
- **Machine Learning:**
  - Clustering: K-Means
  - Dimensionality Reduction: Principal Component Analysis (PCA)
  - Classification: Support Vector Machines (SVM)
- **Other Skills:** EDA, Data Merging, Imputation, Feature Scaling, Elbow Method, Model Tuning

---

## 📁 Repository Structure

<pre>

.
├── code/
│   └── IK+-+Unsupervised+Learning.ipynb         # Main project notebook (Parts A & B)
│
├── dataset/
│   ├── Part1 - Car name.csv                     # Car name information
│   ├── Part1 - Car-Attributes.json              # Car technical specifications
│   └── vehicle.csv                              # Vehicle silhouette classification data
│
├── Problem Statement/
│   └── USL_Problem Statement.pdf                # Project brief with tasks
│
├── .gitignore
└── README.md                                    # This file

</pre>

---

## 💡 Key Learnings

- K-Means clustering and elbow method for unsupervised grouping  
- Visual EDA techniques for pattern discovery  
- Dimensionality reduction with PCA and its assumptions  
- Improved classifier performance through feature compression  
- Classification using SVM and model tuning best practices

---

## ✍️ Author

**Ishant Kundra**  
📧 [ishantkundra9@gmail.com]
🎓 Master’s in Computer Science | AIML Track
