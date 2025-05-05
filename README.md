# cpsc452

## Enhancing Single-Cell Transcriptomic Analysis with Discrete Latent Archetypes

## Overview
This repository contains:
- `CORTEX dataset.ipynb`: A Jupyter/Colab notebook that downloads the dataset, preprocesses it, trains the VQ-VAE model with archetypal regularization, evaluates clustering, and visualizes results.
- `README.md`: This file.

## Dependencies
Install the required Python packages:
```bash
pip install tqdm urllib3 scvi-tools tensorflow numpy pandas scikit-learn matplotlib torch torchvision umap-learn seaborn scipy
