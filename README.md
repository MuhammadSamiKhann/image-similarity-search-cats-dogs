# 🐶🐱 Image Similarity Search – Cats & Dogs

A clean and simple **image similarity search** system using **pre-trained ResNet18** (ImageNet).  
Upload any cat 🐱 or dog 🐶 image as query → get the **top 5 most visually similar** images from the dataset using **cosine similarity** on deep features.

## ✨ Features

- Feature extraction with **ResNet18** (pretrained on ImageNet)
- 512-dimensional image embeddings
- One-time embedding computation (saved for fast reuse)
- Cosine similarity ranking
- Beautiful Jupyter Notebook visualization with Matplotlib

## 📊 Dataset

- **Total images**: 25,000
- **Training set**: 20,000 images
- **Test set**: 5,000 images
- **Classes**: Cats 🐱 and Dogs 🐶

📥 Download:  
[Dog and Cat Classification Dataset – Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)

**Folder structure:**
data/
└── train/
├── cats/
└── dogs/

text## 🛠️ Installation

# Install dependencies
pip install torch torchvision torchaudio
pip install numpy scikit-learn matplotlib pillow tqdm
Requirements: Python 3.8+
GPU optional (but much faster for embedding extraction)
🚀 Quick Start

Clone this repository

Place the dataset in data/train/
Launch Jupyter Notebook

Run all cells in sequence
Set your query image (any cat/dog photo):

Enjoy the results! 🐾

📸 What You'll See

Your query image
Top 5 most similar images
Cosine similarity score for each match

🛠️ Tech Stack

Python
Jupyter Notebook
PyTorch & TorchVision
ResNet18 (pretrained)
NumPy
scikit-learn
Matplotlib & Pillow
tqdm
