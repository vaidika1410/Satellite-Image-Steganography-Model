# Satellite Image Steganography using Deep Learning 🛰️🔐

This project implements a deep learning model to embed 256-bit secrets inside satellite images using an encoder-decoder architecture.

## 🧠 Model Summary
- Encoder embeds secrets inside cover images.
- Decoder reconstructs secrets from stego images.
- Supports evaluation on unseen datasets like CIFAR-10.
- Tracks PSNR, MSE, and bitwise accuracy.

## 🧪 Metrics
- Decoder Accuracy: 95%+
- PSNR: 40+ dB
- Payload: 256 bits / image

## 🚀 Getting Started
```bash
git clone https://github.com/your-username/satellite-steganography.git
cd satellite-steganography
pip install -r requirements.txt
