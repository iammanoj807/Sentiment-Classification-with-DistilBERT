# Sentiment Classification with DistilBERT

This project fine-tunes the lightweight transformer model DistilBERT for binary sentiment classification on the IMDb dataset using HuggingFace Transformers and PyTorch.

## 🧠 Overview

- **Model**: DistilBERT (via HuggingFace)
- **Dataset**: IMDb Movie Reviews (positive/negative sentiment)
- **Accuracy Achieved**: 86.68%
- **F1 Score**: 86.04%
- **Precision**: 90.3%
- **Recall**: 82.16%
- **Training**: 3 epochs, batch size 16
- **Device**: Apple MPS (or CPU/GPU)

## 🚀 How to Run

```bash
# Install required packages
pip install transformers datasets scikit-learn torch
