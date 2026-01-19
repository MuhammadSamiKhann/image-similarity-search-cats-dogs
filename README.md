# 🐶🐱 Image Similarity Search – Cats & Dogs

A simple **image similarity search** system using **pre-trained ResNet18**.  
Upload any cat 🐱 or dog 🐶 image → get the **top 5 most visually similar** images using **cosine similarity**.

## ✨ Features

- Feature extraction with **ResNet18** (pretrained on ImageNet)
- 512-dimensional image embeddings
- One-time embedding computation (saved for fast reuse)
- Cosine similarity ranking
- Jupyter Notebook visualization

## 📊 Dataset

- **Total images**: 25,000 (20,000 train + 5,000 test)
- **Classes**: Cats 🐱 and Dogs 🐶

📥 [Download Dataset from Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)

**Folder structure:**
```
data/
└── train/
    ├── cats/
    └── dogs/
```

## 🛠️ Installation
```
pip install torch torchvision torchaudio
pip install numpy scikit-learn matplotlib pillow tqdm jupyter
```

## 🚀 Quick Start

1. Download dataset and extract to `data/train/`
2. Launch Jupyter: `jupyter notebook`
3. Run all cells in `notebook.ipynb`
4. Upload your query image and see results! 🐾

## 🎯 How It Works

1. **Extract** 512-D features from images using ResNet18
2. **Save** embeddings for fast reuse
3. **Query** with any image
4. **Calculate** cosine similarity
5. **Return** top 5 matches

## 📂 Project Structure
```
image-similarity-search/
├── data/train/          # Dataset folder
├── embeddings/          # Saved embeddings (auto-generated)
├── notebook.ipynb       # Main notebook
└── README.md
```

## 🛠️ Tech Stack

Python • PyTorch • ResNet18 • NumPy • scikit-learn • Matplotlib

## 📄 Author 

Muhammad Sami Khan

---

<div align="center">

⭐ Star this repo if you found it helpful!

</div>
