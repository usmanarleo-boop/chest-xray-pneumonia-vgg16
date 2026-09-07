# chest-xray-pneumonia-vgg16
Pneumonia detection using VGG16 Transfer Learning and Grad-CAM explainability.
# Chest X-Ray Pneumonia Detection using VGG16 & Grad-CAM

An end-to-end Computer Vision system that classifies chest X-rays as Normal or Pneumonia using Transfer Learning with VGG16, featuring Grad-CAM visual interpretability.

## Key Features
- **Dataset:** Kaggle Chest X-Ray (Pneumonia) dataset fetched automatically via `kagglehub`.
- **Model Architecture:** Pre-trained VGG16 base with custom classification layers ($224 \times 224$ input resolution).
- **Explainable AI (Grad-CAM):** Generates side-by-side heatmaps targeting the `block5_conv3` layer to highlight diagnostic regions in lung tissue.

## How to Run
1. Open `main-ipynb.ipynb` in Google Colab.
2. Click **Runtime** -> **Run all**. The dataset will download automatically.
