# 🖼️ Image Captioning Project

This project implements an image captioning model that generates natural language captions for images. It uses deep learning components built with PyTorch, including a CNN image encoder and two types of sequence decoders: **LSTM** and **Transformer**.

---

## ✅ Components Used

### 🧠 Models

- **ResNet-50** (pretrained): Used as the image encoder to extract feature vectors from input images.
- **LSTM Decoder**: A sequence decoder that generates captions using LSTM cells with attention.
- **Transformer Decoder**: Custom-built Transformer decoder using multi-head attention and positional encoding.

---

### 🧰 Libraries Used

- **PyTorch / TorchVision** – Deep learning and pretrained ResNet model
- **NLTK** – Caption tokenization and vocabulary building
- **Datasets (Hugging Face)** – Dataset handling (if used)
- **Pillow** – Image processing
- **OpenCV** – Image manipulation
- **NumPy** – General numerical operations

> 🔸 `ultralytics` and YOLO are **not used** in this project.

---

## 📊 Evaluation Metrics

- **BLEU Score** – Measures the similarity between generated captions and reference captions
- **Word Precision** – Measures overlap between generated and true words

---

## 📁 File

- `image_captioning_transformer_.ipynb` — Main Jupyter notebook containing all code, training, and evaluation logic.

---

