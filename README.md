# 🌿 LeafNet: Binary Segmentation of Plant Leaves using DeepLab

**LeafNet** is a deep learning project focused on **segmenting plant leaves** from natural images using the **DeepLab architecture**. The goal is to accurately identify and isolate leaves for applications such as plant disease detection, phenotyping, and leaf count analysis.

---

## 📁 Dataset

- **Source:** [Kaggle (Plant Leaf Segmentation Dataset)]([url](https://www.kaggle.com/datasets/fakhrealam9537/leaf-disease-segmentation-dataset/versions/4))
- The dataset includes:
  - RGB images of plants
  - Corresponding binary segmentation masks labeling leaf pixels
---

## 🧠 Model Overview: DeepLab

- Architecture: **DeepLabV3+**
- Backbone: **ResNet50** (default)
- Key Components:
  - **Atrous Spatial Pyramid Pooling (ASPP)** for multi-scale context
  - Upsampling for high-resolution segmentation masks
- Output: Pixel-wise binary mask (Leaf vs Background)


