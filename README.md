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
```
## Dataset
The notebook automatically downloads the Linnarsson Lab mouse cortex dataset from:
https://storage.googleapis.com/linnarsson-lab-www-blobs/blobs/cortex/expression_mRNA_17-Aug-2014.txt
and saves it as expression.bin.

## Usage
1.Open CORTEX dataset.ipynb in Jupyter or Google Colab.

2.Run all cells end-to-end.

Note: All explanations and instructions are provided within the notebook itself.
## Citations
- Zeisel, A. et al. Cell types in the mouse cortex and hippocampus revealed by single-cell RNA-seq. *Science* **347**, 1138–1142 (2015).
- van den Oord, A., Vinyals, O. & Kavukcuoglu, K. Neural Discrete Representation Learning. In *NeurIPS* (2017).
- Lopez, R. et al. Deep generative modeling for single-cell transcriptomics. *Nat. Methods* **15**, 1053–1058 (2018).
