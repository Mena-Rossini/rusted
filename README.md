# Nigel: Underwater Rust Detection System

![Nigel Banner](https://example.com/banner-image) <!-- Optional: Add a banner if you have one -->

## 🔍 Project Overview

**Nigel** is an underwater robot module built to identify **rusted pipes and corroded structures in offshore water treatment plants**. This system was developed during the **TANCAM Women's Hackathon 2024** to support sustainable infrastructure maintenance, using computer vision and deep learning.

The module captures underwater imagery and uses an image classification model to detect rusted regions. It automates rust detection in remote or hazardous underwater environments, saving time, cost, and human risk.

---

## 🧠 Features

- 📦 **Image Augmentation** using TensorFlow's `ImageDataGenerator`
- 🎯 **Rust Detection ML Model** trained on augmented underwater pipe datasets
- 🧹 **Directory Management & Batch Processing**
- 📤 **Model Saving & Reloading** for reproducibility
- 🐍 **OpenCV Integration** for preprocessing and visualization
- 📈 Ready for deployment in real-world underwater robotic systems

---

## 💻 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- OS, Shutil (for directory handling)

---

## 🛠️ Software Requirements

| Software         | Version        |
|------------------|----------------|
| Python           | 3.7+           |
| TensorFlow       | 2.11+          |
| OpenCV           | 4.5+           |
| NumPy            | latest         |
| Matplotlib       | latest         |

You can install all required packages using:

```bash
pip install -r requirements.txt
