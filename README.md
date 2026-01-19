🐶🐱 Image Similarity Search – Cats & Dogs

This project is a Jupyter Notebook that implements an image similarity search system using a pre-trained ResNet18 model.
Given a query image (cat or dog), the notebook finds the top 5 most visually similar images from the dataset using cosine similarity.

🔍 How It Works

Uses ResNet18 (ImageNet) as a feature extractor

Converts images into 512-dimensional embeddings

Saves embeddings for fast reuse

Compares images using cosine similarity

Displays results in Jupyter Notebook with matplotlib

📊 Dataset

Total images: 25,000

Training images: 20,000

Test images: 5,000

Classes: Cats 🐱 and Dogs 🐶

Download the dataset from Kaggle (https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)

Directory structure:

data/train/
 ├── cats/
 └── dogs/

🛠️ Installation
1️⃣ Install Required Libraries
pip install torch torchvision numpy scikit-learn matplotlib pillow tqdm


⚠️ Python 3.8+ recommended. GPU optional but faster for embeddings.

▶️ Usage

Open the Jupyter Notebook in this repo:

jupyter notebook


Download and place the dataset in data/train/

Run the cells in order

Set a query image path inside the notebook:

query_image_path = "dog.jpg"


The notebook will display the query image and top 5 similar images with similarity scores.

📌 Output

Query image

Top 5 similar images

Cosine similarity score for each image

🚀 Tech Stack

Python

Jupyter Notebook

PyTorch

TorchVision

ResNet18

NumPy

Scikit-learn

Matplotlib
