# 🚀 Satellite Image Steganography using Deep Learning

This repository hosts the implementation of a deep learning-based steganography detection and classification system. The project explores the encoding and decoding of secret information within satellite images, analyzes their detectability, and aims to build a robust image steganalysis pipeline.

---

## 📌 Project Overview

Steganography is the practice of concealing messages or information within digital media. This research aims to improve the security of hidden data and increase the payload capacity while detecting and classifying such hidden content in images using advanced machine learning models. The project is part of an ongoing internship under the guidance of the **Medicaps University** research team.

### 🧑‍🏫 Supervision Team

* **Supervisor**: Dr. Arun Kumar
* **Co-Supervisors**:

  * Prof. Rashmi Choudhary
  * Prof. Shweta Gupta
* **Coordinator**: Prof. Arpit Deo

### 👩‍💼 Research Team

* **Vaidika Kaul** – Researcher & Developer
* **Gautam Jagthap** – Researcher & Developer

---

## 🌟 Objectives

* Improve the security of data hidden within images.
* Increase the payload capacity of steganographic systems.
* Analyze existing steganography techniques in images.
* Detect and classify whether an image contains steganographic content.
* Compare various machine learning and deep learning models.
* Improve model accuracy, robustness, and efficiency.
* Explore datasets and preprocessing techniques relevant to image steganalysis.

---

## 🧠 Methodology

1. **Literature Survey**: Review of steganography and detection algorithms.
2. **Data Handling**:

   * Preprocessing, normalization, augmentation.
   * Payload embedding using encoder-decoder networks.
3. **Modeling**:

   * CNN-based Encoder and Decoder models
   * Detector model for binary classification (stego vs. normal)
4. **Evaluation Metrics**:

   * PSNR (Peak Signal-to-Noise Ratio)
   * MSE (Mean Squared Error)
   * Bitwise Decoder Accuracy
   * Classification Accuracy, Precision, Recall, F1-Score (for detector)
5. **Visualization**:

   * Heatmaps for hidden patterns
   * Difference maps (cover vs. stego)

---

## 🔬 Example Results

* **Payload Capacity**: 256 bits/image
* **Average PSNR**: \~40+ dB
* **MSE**: < 0.01
* **Decoder Accuracy**: \~95%

---

## 📦 Installation & Setup

```bash
git clone https://github.com/your-username/satellite-steganography.git
cd satellite-steganography
pip install -r requirements.txt
```

---

## 🚀 Usage

Train encoder-decoder:

```bash
python train.py
```

Evaluate:

```bash
python evaluate.py
```

Run detector:

```bash
python detector_train.py
```

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

---

## 🙌 Acknowledgements

This work is supported by **Medicaps University** under its Inhouse Research Internship Program.

We thank all supervisors, mentors, and the Computer Science Department for their valuable support.
