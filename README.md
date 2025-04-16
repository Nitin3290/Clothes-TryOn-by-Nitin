# 👕 Clothes Virtual Try-On

A personal project by **K S Nitin**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nitin3290/Clothes-TryOn-by-Nitin/blob/main/setup_gradio.ipynb)

---

## 📝 What’s This About?

Shopping online? It's hard to tell how clothes will look on you. This tool helps you preview how a t-shirt or dress might fit—just upload a photo of yourself and your outfit, and get a virtual try-on in seconds.

No fancy setup needed. It runs entirely in a notebook and uses pose detection, segmentation, and image processing to generate the output.

---

## 🎬 Demo

https://user-images.githubusercontent.com/63489382/163922795-5dbb0f52-95e4-42c6-95d7-2d965abeba6d.mp4

---

## 🧩 How It Works

The workflow follows a three-stage pipeline:

1. **Preprocessing**: Removes background and prepares your photo.
2. **Pose & Segmentation**: Uses OpenPose to detect body points and U-2-Net for segmenting clothing.
3. **Try-On Generation**: Combines everything with a GAN to generate your try-on look.

---

## 🔧 Block Diagrams

**Overall Flow**
![block_diagram_whole](https://user-images.githubusercontent.com/63489382/163922947-c1677f79-ad6f-4550-affc-7d4e80f0d247.png)

**Detailed Architecture**
![block_diagram_detailed](https://user-images.githubusercontent.com/63489382/163922991-86d148c2-1a97-48a5-b4ec-d8c16819374a.png)

---

## 🚀 Try It Yourself

1. Click the **"Open in Colab"** badge above.
2. Run the notebook `setup_gradio.ipynb`.
3. Upload your image and the outfit.
4. See the result—your virtual look, previewed.

---

## 🙋‍♂️ Created By

**K S Nitin**

GitHub: [@Nitin3290](https://github.com/Nitin3290)

---

## 📄 Cite This Work

