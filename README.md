# 🍽️ Zomato Restaurant Clustering using NLP and Unsupervised Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-green)
![Clustering](https://img.shields.io/badge/Unsupervised-Clustering-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# 📌 Project Overview

This project applies **Natural Language Processing (NLP)** and **Unsupervised Machine Learning** techniques to cluster restaurants based on customer reviews. By grouping restaurants with similar review patterns, the project helps identify customer preferences, improve restaurant recommendations, and generate valuable business insights.

---

# 🎯 Problem Statement

Restaurant review data is unstructured and unlabeled, making traditional supervised learning unsuitable. The objective of this project is to preprocess customer reviews, transform text into numerical features, and cluster similar restaurants using unsupervised machine learning algorithms.

---

# 📂 Dataset

This project uses two datasets:

- **Zomato Restaurant reviews.csv**
- **Zomato Restaurant names and Metadata.csv**

> **Note:** The datasets are intentionally excluded from this repository using `.gitignore`. Place them in your Google Drive or local project folder before running the notebook.

---

# ⚙️ Project Workflow

```text
Restaurant Reviews
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Text Preprocessing (NLP)
        │
        ▼
TF-IDF Vectorization
        │
        ▼
PCA (Dimensionality Reduction)
        │
        ▼
Clustering Algorithms
(K-Means | Hierarchical | DBSCAN)
        │
        ▼
Model Evaluation
(Silhouette Score)
        │
        ▼
Business Insights
```

---

# 🤖 Machine Learning Models

- K-Means Clustering
- Hierarchical Clustering
- DBSCAN

---

# 📊 Model Performance

| Model | Silhouette Score | Performance |
|--------|-----------------:|-------------|
| K-Means | 0.043 | Poor |
| Hierarchical Clustering | 0.326 | Good |
| DBSCAN | 0.330 | ⭐ Best |

**Final Model Selected:** **DBSCAN**

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- WordCloud
- Scikit-learn

---

# 📈 Key Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- NLP Text Preprocessing
- TF-IDF Feature Extraction
- PCA for Dimensionality Reduction
- K-Means Clustering
- Hierarchical Clustering
- DBSCAN Clustering
- Hyperparameter Tuning
- Model Evaluation using Silhouette Score
- Business Insights & Recommendations

---

# 💼 Business Impact

This project helps businesses:

- Understand customer preferences.
- Identify restaurants with similar customer experiences.
- Improve restaurant recommendation systems.
- Design targeted marketing campaigns.
- Support data-driven decision making.

---

# 🚀 Future Enhancements

- Implement BERT or Sentence Transformer embeddings.
- Build an intelligent restaurant recommendation system.
- Deploy the project as a web application.
- Include restaurant ratings and additional metadata.
- Explore advanced clustering techniques.

---

# 📁 Repository Structure

```
Zomato-Restaurant-Clustering/
│
├── Zomato_Restaurant_Clustering.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

# ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/nandini-18-ai/Zomato-Restaurant-Clustering.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Place the datasets

Copy the following files into your Google Drive or project folder:

- Zomato Restaurant reviews.csv
- Zomato Restaurant names and Metadata.csv

### 4. Open the notebook

Run the notebook using:

- Google Colab
- Jupyter Notebook

---

# 📌 Repository Information

- Repository Name: **Zomato-Restaurant-Clustering**
- Language: Python
- Project Type: Unsupervised Machine Learning
- Domain: Restaurant Analytics & NLP

---

# 👨‍💻 Author

**Nandini Dhole**

Bachelor of Engineering (Artificial Intelligence & Data Science)

---

## ⭐ If you found this project useful, consider giving it a star.
