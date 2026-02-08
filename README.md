# Elevate_Lab13

# Task 13: PCA – Dimensionality Reduction

## 📌 Objective
The goal of this task is to understand **Principal Component Analysis (PCA)** and how it helps in:
- Reducing high-dimensional data
- Preserving maximum variance
- Improving computational efficiency
- Analyzing the trade-off between dimensionality and model accuracy

---

## 📊 Dataset
**Sklearn Digits Dataset**
- Total samples: 1797
- Image size: 8 × 8 grayscale images
- Original features: 64 (flattened pixels)
- Target: Digit labels (0–9)

---

## 🛠 Tools & Technologies Used
- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Google Colab

---

## 🔍 Approach Followed

1. Loaded the Digits dataset and flattened image data into feature vectors.
2. Applied **StandardScaler** to normalize features before PCA.
3. Performed PCA with different numbers of components: **2, 10, 30, 50**.
4. Calculated and plotted **cumulative explained variance** to analyze information retention.
5. Trained a **Logistic Regression** model on:
   - Original dataset (without PCA)
   - PCA-reduced datasets
6. Compared classification accuracy before and after dimensionality reduction.
7. Visualized data using **2D PCA scatter plot**.
8. Saved all plots, reduced datasets, and results automatically for reporting.

---

## 📈 Results & Observations

- PCA significantly reduced the number of features while retaining most of the variance.
- Around **30 principal components** preserved more than **95% of the variance**.
- Classification accuracy with PCA was comparable to the baseline model.
- PCA helped in reducing computational complexity with minimal performance loss.

---

outputs/
│
├── plots/
│ ├── pca_explained_variance.png
│ └── pca_2d_scatter.png
│
├── data/
│ └── reduced_digits_pca30.csv
│
└── results/
└── pca_accuracy_comparison.csv

##outputs:

<img width="963" height="669" alt="Image" src="https://github.com/user-attachments/assets/61fdc24f-9469-464c-9c76-24f3992e949c" />
<img width="508" height="271" alt="Image" src="https://github.com/user-attachments/assets/4c710628-4543-4bce-bdfa-c59420e18f9e" />
<img width="830" height="722" alt="Image" src="https://github.com/user-attachments/assets/75840670-ea9e-48d7-b90a-48ee9cee2b67" />

