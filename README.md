# FashionFinder-CNN

FashionFinder-CNN is a Python project that allows you to find visually similar clothing items from the Fashion-MNIST dataset using a Convolutional Neural Network (CNN) and cosine similarity. You can upload any grayscale fashion image (T-shirt, dress, bag, etc.) and see the top 5 similar items from the dataset.

---

## Features

- **CNN-based feature extractor**: Extracts 128-D embeddings for Fashion-MNIST images.
- **Similarity search**: Uses cosine similarity to find closest matches.
- **Confusion matrix**: Evaluates classifier performance on test set.
- **Live query**: Upload any fashion image and get top 5 similar items.
- **Visualization**: Displays the query image alongside top 5 similar images.

---

## Installation

```bash
# Install dependencies
pip install torch torchvision pillow scikit-learn matplotlib
