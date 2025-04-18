# 💸 Banknote Clustering Using K-Means

This project uses the **K-Means clustering algorithm** to group banknotes based on statistical features — without using any labels. The goal is to explore if clustering can help identify real vs. fake notes using unsupervised learning.

---

## 📊 Dataset

The dataset contains numerical features extracted from banknote images (e.g., variance, skewness, etc.). There are no labels in the clustering task.

- **Total Records**: 1372
- **Features Used**: V1, V2 (or more if you used them)

---

## 🧠 What I Did

- Preprocessed the data using normalization
- Applied the **Elbow Method** to find the optimal number of clusters (k = 2)
- Ran **K-Means clustering**
- Visualized the clusters and centroids
- Interpreted the clustering result as possible real/fake separation

---

## 📈 Results

![KMeans Clustering Plot](<img width="428" alt="Image" src="https://github.com/user-attachments/assets/f913cc17-7b9e-434e-b6bb-5fd77aee44aa" />) <!-- Replace with your actual path -->

The model discovered **two distinct groups** in the data:

- The upper cluster likely represents **fake notes**
- The lower cluster likely represents **real notes**
- Centroids (red stars) show the center of each group

Even without knowing which notes were real or fake, the model found **clear structure** in the dataset.

---

## 🛠️ Tools Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook / Google Colab

---

## 🔗 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/banknote-kmeans.git
