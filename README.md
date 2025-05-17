# ComputerVisionAssignments

# Deep Learning & Transfer Learning Assignment

---

## Overview
This repo hosts Colab notebooks demonstrating:
- **Part 1**: Supervised Contrastive Learning vs. Softmax Classification
- **Part 2**: Transfer Learning on Images, Audio, Video, and Text
- **Part 3**: Zero-Shot Learning (CLIP & BiT)
- **Part 4**: Vision Models on MNIST/Fashion-MNIST/CIFAR-10 & Medical Imaging

---

## Prerequisites
- Google Colab or local Jupyter with GPU
- Python 3.7+ with:
  - TensorFlow 2.x, TensorFlow Hub, tensorflow-addons
  - NumPy, Matplotlib, Pandas, tensorflow-datasets
  - OpenAI CLIP (for Part 3)

---

## Structure

- Part 1: Supervised Contrastive vs Softmax
- Part 2: Transfer Learning
- Part 4: Vision Models
---

## Part Highlights

### Part 1
- Compare supervised contrastive loss (TFA SupConLoss) vs. softmax on an image dataset
- Visualize training curves, embeddings (t-SNE), and confusion matrices

### Part 2
- **Images**: Feature-extractor vs. fine-tune (EfficientNet/MobileNet)
- **Audio**: YamNet embeddings
- **Video**: TF Hub action recognition
- **Text**: TF Hub text encoders (BERT)

### Part 3
- Zero-shot classification with CLIP
- Transfer with Big Transfer (BiT) on Flowers dataset

### Part 4
- **Standard**: Transfer EfficientNet & BiT on MNIST, Fashion‑MNIST, CIFAR‑10; explore MLP‑Mixer & ConvNeXt
- **Medical**: X‑ray pneumonia (2D CNN), 3D CT scan classification

### Links:
[Colab](https://colab.research.google.com/drive/1rC6l5JKubuhS10mDJyWC4DLklsCV2lnz#scrollTo=CEyK7ZkiLMAq)
[Demo Video](https://www.youtube.com/watch?v=s8r-9HF3lj0)


