# ViT-Paper-Replication

This repository contains a Jupyter notebook attempting to replicate the Vision Transformer (ViT) architecture from the paper ["An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale"](https://arxiv.org/abs/2010.11929) using PyTorch. The implementation loads the Food101 dataset for image classification, sets random seeds for reproducibility, and prepares the environment for training a transformer-based model on GPU/CPU.

**Note**: The provided notebook appears incomplete (e.g., missing full ViT model definition, patch embedding, transformer blocks, training loop). See the Notes section for completion suggestions.

## Overview
- **ViT_Paper_replication.ipynb**: Imports PyTorch libraries, sets seeds, loads Food101 train/test datasets from torchvision (downloads ~5GB), and sets up device (CUDA if available).
- Key Components (Partial):
  - Dataset: Food101 (101 food classes, ~75k train images, ~25k test).
  - Environment: PyTorch with CUDA support.
  - Goal: Replicate ViT's patch-based transformer for vision tasks.

This is an educational replication; for full production use, refer to official implementations like in timm or Hugging Face Transformers.

## Prerequisites
- Python 3.x
- Libraries: `torch`, `numpy`, `torchvision`
