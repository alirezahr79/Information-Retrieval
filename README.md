# 📚 Advanced Recommender System

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000" alt="Hugging Face Transformers">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python">
  <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter Notebook">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge" alt="License">
</p>

> Welcome to the Advanced Recommender System project!

The **Advanced Recommender System** is a comprehensive platform designed to streamline the process of retrieving, classifying, ranking, and recommending academic documents tailored to user preferences. Whether you're conducting research or exploring literature, this system aims to enhance your workflow with cutting-edge methodologies.

---

| **Source Code** | **Website** |
|:-----------------|:------------|
| <a href="https://github.com/deepmancer/advanced-recommender-system" target="_blank">github.com/deepmancer/advanced-recommender-system</a> | <a href="https://deepmancer.github.io/advanced-recommender-system/" target="_blank">deepmancer.github.io/advanced-recommender-system</a> |

---

## ✨ Key Features:
- End-to-end pipeline for academic document retrieval and recommendation.
- Integration of machine learning and deep learning models, clustering techniques, and advanced search algorithms.
- Personalized search and recommendation for tailored user experiences.

---

## 🔍 Overview

The project pipeline is divided into three core phases:

1. **📥 Data Collection & Indexing Infrastructure**:
   - Collect and preprocess data for efficient retrieval.
   - Build robust indexing and retrieval systems with spell correction and vector space models.

2. **🧠 Machine Learning & Clustering**:
   - Leverage classification algorithms and clustering techniques to improve document categorization and organization.

3. **🌐 Web Crawling & Personalized Recommendations**:
   - Enhance the system by incorporating web crawling, link analysis, and personalized recommendation engines.

---

## 🛠️ Workflow Phases

### 📂 Phase 1: Data Acquisition and Indexing Infrastructure

In this phase, we establish a strong foundation for data processing and retrieval. 

**Datasets**:
- Source: [Semantic Scholar](https://www.semanticscholar.org/)
- Focus: Artificial Intelligence & Bioinformatics

**Key Components**:
- 🛠️ **Data Preprocessing**: Structuring academic papers for indexing.
- 📍 **Positional Index Construction**: Creating a positional index for precise search results.
- ✏️ **Spell Correction**: Bigram-based system to correct typos in queries.
- 📐 **Vector Space Modeling**:
  - `ltn-lnn`: Term frequency normalization.
  - `ltc-lnc`: Adjustments for term and document frequency.
  - `Okapi BM25`: Probabilistic ranking model.
- 📈 **Evaluation Metrics**: Metrics such as MRR, Precision, Recall, F1 Score, MAP, and nDCG ensure robust performance analysis.

---


### 🧬 Phase 2: Machine Learning and Clustering for Document Retrieval

This phase enhances search capabilities with classification and clustering techniques.

**Datasets**:
- Source: [Kaggle ArXiv Abstracts](https://www.kaggle.com/datasets/spsayakpaul/arxiv-paper-abstracts?resource=download)

**Key Components**:
- 🗂️ **Naive Bayes Classification**: Basic categorization of documents.
- 🤖 **Neural Network Classifier**: Improved accuracy for document classification.
- 🔍 **Large Language Models**: Fine-tuned models for advanced categorization.
- 🗂️ **Hierarchical Clustering**: Organizing documents into meaningful groups.

---

### 🕸️ Phase 3: Web Crawling, Link Analysis, and Personalized Search

The final phase focuses on enriching data and delivering personalized recommendations. 

**Key Components**:
- 🕷️ **Web Crawling**: Gathering additional data from academic sources.
- 🔗 **Link Analysis**:
  - **PageRank**: Measure document importance.
  - **HITS**: Identify hubs and authorities in document networks.
- 🧠 **Recommendation Engines**:
  - **Content-Based Filtering**: Recommend articles based on similarity.
  - **Collaborative Filtering**: Suggest articles based on user preferences.
- 📈 **Evaluation Metrics**: Metrics like nDCG assess recommendation quality.


### 🌟 Final Deliverable

A powerful and user-friendly recommender system capable of retrieving, organizing, ranking, and recommending academic articles.

---

## 📝 License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code while adhering to the terms of the license.

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:
1. **Star the repository** ⭐ to show your support.
2. **Fork the repository** 🍴 and implement new features or fixes.
3. Submit a **pull request** 🔄 with your contributions.
