# Lightweight ViT-based Deepfake Detector

This project implements a lightweight Vision Transformer (ViT) model for binary classification of real vs fake (deepfake) videos. It is optimized to run on limited GPU resources using average frame pooling and Focal Loss.

## 📦 Features
- Vision Transformer (ViT) backbone (vit_b_16)
- Average frame pooling across 30 frames per video
- Focal Loss for class imbalance
- Lightweight setup for GPUs with 4GB memory

## 🚀 Installation

```bash
git clone https://github.com/panosdrama/ViT-deepfake-detector.git
cd ViT-deepfake-detector
pip install -r requirements.txt
```

## 🧪 Run Training

Place your real and fake videos inside:

```
datasets/
├── videos_real/
└── videos_fake/
```

Then run:

```bash
python main.py
```

## 📄 Citation

If you use this code, please cite the corresponding paper:

> Panos Stampas, "Lightweight ViT-based Architecture for Deepfake Video Classification on Limited GPUs", 2024.

