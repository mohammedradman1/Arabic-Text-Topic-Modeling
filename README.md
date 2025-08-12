# Arabic-Text-Topic-Modeling
Arabic Text Topic Modeling: A Comparative Analysis of Latest Techniques

🧭 Overview

This project investigates Arabic topic modeling using:

BERTopic (BERT embeddings + c‑TF‑IDF + UMAP + HDBSCAN)

LDA and NMF (probabilistic and matrix factorization)

K‑Means and DBSCAN (clustering baselines)

Predicted clusters are evaluated against true labels using AMI.

---

📦 Dataset

Source: Kaggle — DataSet for Arabic Classification 

Size: 111,728 MSA documents across 5 categories: sports, politics, culture, economy, diverse.

Preprocessing: Arabic stop‑word removal (NLTK). Optional advanced preprocessing (diacritics/tatweel removal, punctuation/number stripping, letter normalization) can be applied.
  
Link: [link]([https://www.linkedin.com/in/mrm1/](https://www.kaggle.com/datasets/saurabhshahane/arabic-classification)) 


🛠️ Preliminary Requirements

This project requires the following setup before running:

Python Environment
Python 3.10 or later.

Required Packages
Install all dependencies:
<code> pip install pandas numpy scikit-learn nltk bertopic sentence-transformers umap-learn hdbscan matplotlib </code>


