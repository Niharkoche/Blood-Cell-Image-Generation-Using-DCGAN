# 🧬 Blood Cell Image Generation using DCGAN
A Deep Convolutional GAN (DCGAN) project for generating synthetic blood cell images using TensorFlow and Keras, demonstrating adversarial training and image synthesis.
## 🚀 Overview

This project implements a **Deep Convolutional Generative Adversarial Network (DCGAN)** to generate realistic synthetic blood cell images. Built using TensorFlow and trained on a real-world dataset, the model learns to create new images from random noise through adversarial learning.

---

## 🧠 How It Works

A GAN consists of two neural networks competing with each other:

* **Generator 🖌️**: Creates fake images from random noise
* **Discriminator 🔍**: Distinguishes between real and fake images

Over time, the generator improves and produces increasingly realistic images.

---

## 🛠️ Tech Stack

* Python 🐍
* TensorFlow / Keras 🤖
* OpenCV 📷
* NumPy
* Matplotlib 📊
* Google Colab ☁️

---

## 📂 Dataset

* Blood Cell Images Dataset (via KaggleHub)
* Images resized to **64×64** and normalized for training

---

## ⚙️ Model Architecture

### 🔹 Generator

* Dense Layer → Reshape
* Conv2DTranspose Layers
* Batch Normalization + LeakyReLU
* Outputs RGB image (64×64×3)

### 🔹 Discriminator

* Conv2D Layers
* Dropout for regularization
* Fully Connected Layer (Binary Classification)

---

## 🔥 Key Features

✔️ Image preprocessing & normalization
✔️ Label smoothing for stable training
✔️ Custom loss functions
✔️ Accuracy tracking (Generator & Discriminator)
✔️ Visualization of generated images

---

## ▶️ Run the Project

You can directly run this project on Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19uCxCEIH8C05uNhPXJFF8Rt97aiSOM1z?usp=sharing)

---

## 📊 Output

* Generates synthetic blood cell images from random noise
* Evaluates model performance using discriminator accuracy
* Visualizes generated samples after training

---

## 🚀 Future Improvements

* Implement **WGAN / StyleGAN** for better quality
* Train on higher resolution images
* Improve training stability
* Deploy as a web app

---

## 👨‍💻 Author

**Nihar Koche**
B.Tech Student | AI & ML Enthusiast

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to contribute!
