# 🎬 Film Recommendation System — SVD Collaborative Filtering

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Improvement](https://img.shields.io/badge/Relevance%20Improvement-+30%25-brightgreen?style=flat-square)

> **SVD-based collaborative filtering** on 10,000+ user-item records — **+30% relevance** over popularity baseline.

---

## 📋 Overview

A matrix factorization recommender system using Singular Value Decomposition (SVD) on user-movie rating data. Learns latent user preferences and item characteristics beyond explicit ratings.

## 🎯 Results

| Metric | Value |
|--------|-------|
| Algorithm | SVD (Matrix Factorization) |
| Dataset | 10,000+ user-item ratings |
| **Improvement** | **+30% relevance vs popularity baseline** |
| Evaluation | RMSE |

## 🔧 How It Works

```
User-Item Rating Matrix  (sparse)
          ↓
SVD Decomposition  →  U · Σ · Vᵀ
          ↓
Latent Feature Vectors (users & items)
          ↓
Predict missing ratings  →  Top-N recommendations
```

## 🔧 Key Techniques

- ✅ SVD matrix factorization
- ✅ RMSE evaluation
- ✅ Comparison vs popularity-based baseline
- ✅ Top-N recommendation generation
- ✅ Cold-start analysis

## 🚀 Run

```bash
pip install -r requirements.txt
jupyter notebook film_recommendation.ipynb
```

---

## 👤 Author

**Yousef Mohamed Yousef**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/yousef--mohamed--/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Profile-20BEFF?style=flat-square&logo=kaggle)](https://www.kaggle.com/yousefmohamedjoe)
[![GitHub](https://img.shields.io/badge/GitHub-J0e2-181717?style=flat-square&logo=github)](https://github.com/J0e2)

