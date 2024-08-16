# 📚 Advanced Recommender System

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-1.13.1-#EE4C2C?logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Hugging%20Face%20Transformers-4.28.0-#E24C6A?logo=transformers&logoColor=white" alt="Hugging Face Transformers">
  <img src="https://img.shields.io/badge/scikit--learn-1.2.2-#F7E03C?logo=scikit-learn&logoColor=black" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Jupyter%20Notebook-6.4.8-#F37626?logo=jupyter&logoColor=white" alt="Jupyter Notebook">
</p>

Welcome to the **Advanced Recommender Systems**!

---

## 🚀 Project Overview

Our goal is to create a comprehensive platform that excels in retrieving, classifying, ranking, and recommending documents tailored to user preferences. The pipeline of the project follows these key stages:

1. **Data Collection & Preprocessing**: 
   - 📥 **Data Collection**: Gather academic paper data.
   - 🔧 **Preprocessing**: Prepare data for indexing.

2. **Indexing & Retrieval Infrastructure**: 
   - 🗂️ **Indexing**: Develop an indexing system.
   - ✏️ **Spell Correction**: Integrate spell correction mechanisms.
   - 📊 **Vector Space Models**: Apply models for accurate search ranking.

3. **Machine Learning & Clustering**: 
   - 🤖 **Machine Learning**: Implement classification algorithms.
   - 🧩 **Clustering**: Organize documents into clusters.

4. **Web Crawling & Personalized Search**: 
   - 🌐 **Web Crawling**: Collect additional data from the web.
   - 🔍 **Personalized Search**: Develop advanced search and recommendation features.

5. **Evaluation & Optimization**: 
   - 📈 **Evaluation**: Assess system performance using metrics.
   - 🔧 **Optimization**: Refine and improve system effectiveness.

---

## 🏗️ Phase 1: Data Acquisition and Indexing Infrastructure

Phase 1 focuses on laying the foundation for a robust information retrieval system by establishing an efficient data processing and indexing infrastructure.

### Datasets

- **Dataset**: Scientific articles from [Semantic Scholar](https://www.semanticscholar.org/).
- **Dataset Category**: Artificial Intelligence & Bioinformatics

### Key Components

- **📂 Data Preprocessing & Preparation**: Structure academic papers for efficient retrieval.
- **📚 Positional Index Construction**: Create a positional index for precise document searches.
- **🔠 Spell Correction Integration**: Integrate a bigram-based spell correction system.
- **🧮 Vector Space Modeling**: Implement vector space models for effective document ranking:
  - **`ltn-lnn`**: Term frequency normalization model.
  - **`ltc-lnc`**: Term and document frequency adjustment model.
  - **`Okapi BM25`**: Probabilistic relevance ranking model.
- **📈 Evaluation Metrics**: Assess system performance with metrics like MRR, Precision, Recall, F1 Score, MAP, and NDCG.

---

## 🧬 Phase 2: Machine Learning and Clustering for Document Retrieval

In Phase 2, we enhance retrieval capabilities through machine learning techniques, improving classification and clustering to refine the search system.

### Key Components

- **📂 Dataset**: Access the scientific articles dataset from [Kaggle](https://www.kaggle.com/datasets/spsayakpaul/arxiv-paper-abstracts?resource=download).
- **📊 Naive Bayes Classification**: Implement a Naive Bayes classifier for document categorization.
- **🤖 Neural Network Classifier**: Develop a neural network classifier for improved accuracy.
- **🧠 Large Language Models**: Fine-tune a pre-trained model for advanced classification.
- **🧮 Hierarchical Clustering**: Apply hierarchical clustering for document organization.

---

## 🛠️ Phase 3: Web Crawling, Link Analysis, and Personalized Search

Phase 3 centers on expanding the system’s capabilities with web crawling, link analysis, and advanced personalization features.

### Key Components

- **🕷️ Web Crawling**: Deploy a web crawler to gather academic articles and related data.
- **🔗 Link Analysis**: Utilize PageRank and HITS algorithms to determine article importance.
- **📚 Content-Based Recommendation**: Develop recommendations based on article content similarity.
- **🤝 Collaborative Filtering**: Recommend articles based on the preferences of similar users.
- **🧪 Evaluation of Recommender Systems**: Measure recommendation system performance using metrics like nDCG.

### Final Product

Upon completion of Phase 3, the Advanced Recommender Systems will be a comprehensive tool that excels in retrieving, organizing, ranking, and recommending academic papers tailored to users' research needs.

---

## 📝 License

This project is licensed under the MIT License. For detailed information, please refer to the [LICENSE](LICENSE) file.

---

Thank you for your interest in the **Advanced Recommender Systems**! We hope this project serves as a valuable and engaging tool for your research and information retrieval needs. Happy exploring! 🚀
