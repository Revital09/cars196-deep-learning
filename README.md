
---

## 🧠 Part 1: Transfer Learning

- 🔸 Used pretrained `ResNet50`
- 🔸 Fine-tuned on Cars196 dataset
- 🔸 Added classification head (Dense + Dropout)
- 🔸 Achieved strong top-1 accuracy with minimal training time

📦 **Tech:** PyTorch, torchvision, image augmentations

---

## 🔎 Part 2: Image Retrieval

- 🔸 Extracted features using pretrained ResNet
- 🔸 Indexed embeddings with **FAISS** for similarity search
- 🔸 Evaluated retrieval accuracy using top-k matching

📦 **Tech:** ResNet + FAISS + NumPy

---

## 🏁 Part 3: End-to-End CNN Network

- 🔸 Designed and trained a full CNN architecture from scratch
- 🔸 Included convolutional blocks, batch normalization, dropout
- 🔸 Used early stopping and learning rate scheduling

📦 **Tech:** PyTorch (nn.Module), torchmetrics, manual training loop

---

## 📊 Evaluation

- ✅ Accuracy, MAP@k, top-k retrieval score
- ✅ Early stopping, loss visualization
- ✅ Feature vector visualization (optional)

---

## 📁 Dataset

Cars196 contains 16,185 images across 196 car classes, split into:

- 98 training classes (8,144 images)
- 98 test classes (8,041 images)

---

> Developed by Revital Yusupov — 2025
