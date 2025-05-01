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

- [Part 1: Supervised Contrastive vs Softmax]

   - (https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/Part_1_SCL_vs_Softmax.ipynb)

- Part 2: Transfer Learning
  - [Text](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/Part_2_Transfer_Learning/text.ipynb)
  
  - [Part 3: Zero-Shot Learning](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/Part_3_Zero_Shot.ipynb)
- Part 4: Vision Models
   - [3D CT Scan](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/Part_4_Vision/ct_scan_3d.ipynb)


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


