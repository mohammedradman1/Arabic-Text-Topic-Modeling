# Arabic-Text-Topic-Modeling  
Arabic Text Topic Modeling: A Comparative Analysis of Latest Techniques  

## 🧭 Overview
This project investigates Arabic topic modeling using:  

- **BERTopic** (BERT embeddings + c-TF-IDF + UMAP + HDBSCAN)  
- **LDA** and **NMF** (probabilistic and matrix factorization)  
- **K-Means** and **DBSCAN** (clustering baselines)  

Predicted clusters are evaluated against true labels using **AMI**.  

## 🗂️ Project Structure
The project is divided into six main sections as follows:  

1. ✏️ **Text Preprocessing** – Cleaning and preparing the Arabic text (stopword removal, normalization, etc.)  
2. 🔤 **Embedding** – Converting text into numerical vectors (e.g., BERT embeddings, TF-IDF).  
3. 📉 **Dimensionality Reduction** – Reducing feature space (e.g., UMAP) for efficiency and visualization.  
4. 🧩 **Clustering** – Grouping similar documents (e.g., HDBSCAN, K-Means, DBSCAN).  
5. 📚 **Topic Representation (Topic Modeling)** – Extracting and representing main topics from clusters.  
6. 📊 **Evaluation of Topic Modeling** – Measuring quality using metrics like Adjusted Mutual Information (AMI) and Topic Coherence.  

## 📦 Dataset
- **Source:** Kaggle — *DataSet for Arabic Classification*  
- **Size:** 111,728 MSA documents across 5 categories: sports, politics, culture, economy, diverse.  
- **Preprocessing:** Arabic stop-word removal (NLTK). Optional advanced preprocessing (diacritics/tatweel removal, punctuation/number stripping, letter normalization) can be applied.  
- **Link:** [Kaggle Dataset](https://www.kaggle.com/datasets/saurabhshahane/arabic-classification)  

## 🛠️ Preliminary Requirements
This project requires the following setup before running:  

- 🐍 **Python Environment** – Python **3.10** or later  
- 📦 **Required Packages:**  
```bash
pip install pandas numpy scikit-learn nltk bertopic sentence-transformers umap-learn hdbscan matplotlib
