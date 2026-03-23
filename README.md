# Sentiment Analysis using RNN (PyTorch)

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-1.13-orange?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=yellow" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-%23F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter">
</p>

## 📌 **Project Overview**
This project implements **Sentiment Analysis** on the **IMDB Movie Reviews dataset** using a **Recurrent Neural Network (RNN)** built with PyTorch. The model classifies movie reviews as **positive** or **negative** with ~**85% accuracy**.

## 🚀 **Features**
- 🔤 Complete text preprocessing pipeline:
  - Lowercasing, URL/punctuation/HTML removal
  - Stopwords removal, stemming
  - TF-IDF vectorization (5000 features)
- 🧠 Custom RNN architecture (many-to-one)
- 📊 Training with Adam optimizer + Binary Cross Entropy
- 🎯 Test accuracy reporting

## 🛠️ **Tech Stack**
| Category | Technologies |
|----------|--------------|
| Framework | PyTorch |
| Processing | Pandas, Scikit-learn, NLTK |
| Environment | Jupyter Notebook |
| Data Format | CSV (50K reviews) |

## 📂 **Dataset**
- **IMDB Movie Reviews** (50,000 reviews)
- Columns: `review` (text), `sentiment` (positive/negative)
- Size: ~49,582 after deduplication
- Auto-downloaded in notebook

  
## ▶️ How to Run
1. Install dependencies:
   ```bash
    pip install torch pandas scikit-learn nltk jupyter
2. Run notebook:
   ```bash
    jupyter notebook Sentiment_Analysis_RNN.ipynb


## 📊 Output
- Epoch 10/10 loss: 0.1745
- Test Accuracy: 85.42%

