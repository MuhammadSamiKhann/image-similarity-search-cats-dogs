🐶🐱 Image Similarity Search – Cats & Dogs

This project implements an image similarity search system using a pre-trained ResNet18 model.
Given a query image (cat or dog), the system retrieves the top 5 most visually similar images from the dataset using cosine similarity.

🔍 How It Works

Uses ResNet18 (ImageNet) as a feature extractor

Converts images into 512-dimensional embeddings

Saves embeddings for fast reuse

Compares images using cosine similarity

Displays results with similarity scores

📊 Dataset

Total images: 25,000

Training images: 20,000

Test images: 5,000

Classes: Cats 🐱 and Dogs 🐶

Directory structure:

data/train/
 ├── cats/
 └── dogs/

🛠️ Installation
1️⃣ Install Required Libraries
pip install torch torchvision numpy scikit-learn matplotlib pillow tqdm


⚠️ Make sure Python 3.8+ is installed.
GPU (CUDA) is optional but recommended for faster embedding extraction.

▶️ Usage

Place the dataset inside data/train/

Run the notebook cells in order

Set a query image path:

query_image_path = "dog.jpg"


View the top 5 similar images with similarity scores
