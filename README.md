# Clustering with Neural Networks on MNIST

This project implements unsupervised clustering using an autoencoder-based neural network on the MNIST dataset, powered by the Hugging Face Datasets library.

## 🔍 Overview

We trained a simple autoencoder to extract compressed 64-dimensional embeddings of handwritten digits and applied clustering algorithms (K-Means and DBSCAN) to group similar digits.

## 📦 Tools & Libraries

- PyTorch
- Hugging Face `datasets`
- scikit-learn
- Matplotlib
- t-SNE

## 📁 Project Structure

- `notebook/`: Jupyter notebook with the full workflow
- `plots/`: t-SNE cluster visualizations
- `report/`: LaTeX and PDF project report
- `saved_models/`: Optional saved encoder model

## 📊 Results

- **K-Means Silhouette Score:** 0.0903
- **DBSCAN Silhouette Score:** -0.3330

## 📌 Applications

- Digit grouping
- Feature extraction for downstream tasks
- Real-world clustering of unlabelled image data

## 🧠 Author

Submitted by Sabbir Ahmad — AI Clustering Project, April 2025

## 📝 License

This project is shared for educational and demonstration purposes.
