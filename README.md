# 🎬 Netflix Content Clustering

## 📌 Overview
This project applies unsupervised machine learning techniques to cluster Netflix titles into similar groups based on their attributes (such as genre, duration, and ratings).  
**Goal:** Explore content patterns, identify similar shows/movies, and provide insights into Netflix’s library.

---

## 📂 Dataset

**Source:** Netflix dataset (CSV format) containing details like:
- **Title**
- **Genre**
- **Release year**
- **Duration**
- **Ratings**

**Preprocessing:**
- Handling missing values
- Encoding categorical features
- Scaling numerical data

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Clustering algorithms (K-Means)
- **Jupyter Notebook** – Development environment

---

## 🚀 Steps Performed

1. **Data Loading:** Import Netflix dataset.
2. **Data Cleaning:** Handle null values, remove duplicates, standardize formats.
3. **Feature Engineering:** Transform categorical data into numerical form.
4. **Exploratory Data Analysis (EDA):** Visualize patterns in genres, ratings, and durations.
5. **Clustering:** Apply K-Means to group similar titles.
6. **Cluster Analysis:** Interpret clusters to understand content patterns.

---

## 📊 Results & Insights

- Titles are grouped into clusters based on similar features.
- Patterns emerge in content type and genre preferences.
- Clustering can be used for content recommendation and trend analysis.

---

## 📌 How to Run

**Clone the Repository**
```bash
git clone https://github.com/jashwin17/Netflix_Clustering.git
cd netflix-clustering
```

**Install Dependencies**
```bash
pip install -r requirements.txt
```

**Run the Notebook**
```bash
jupyter notebook Netflix_Clustering.ipynb
```