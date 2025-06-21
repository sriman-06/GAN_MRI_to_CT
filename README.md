# GAN for MRI to CT Image Translation 🧠➡️🦴

This project implements a GAN-based image-to-image translation from **brain MRI to CT scans** using the **SynthRAD2023** dataset. Developed as a Capstone Project for the Deep Learning Summer School.

## 📘 Notebook
- `GAN_FOR_MRI_TO_CT(image_resolution).ipynb`: Main Colab notebook including preprocessing, model definition, training, and evaluation.

## 📂 Dataset
- Dataset: [SynthRAD2023 - Zenodo](https://zenodo.org/record/8268565)
- Contains paired, rigidly-aligned MRI and CT slices.

## 🧠 Architecture
- **Model**: Pix2Pix GAN  
  - Generator: U-Net  
  - Discriminator: PatchGAN  
- **Loss**: L1 + GAN Loss (BCE)

## 📊 Metrics (on Subject 1BB028)
- Mean SSIM: **0.86**
- Mean PSNR: **22.5 dB**

## 🚀 How to Run (on Colab)
1. Upload the dataset to your Google Drive.
2. Mount the drive and set the dataset path in the notebook.
3. Run the notebook cells step-by-step.
4. View generated CT outputs at the end.

## 🙋‍♂️ Author
Sriman Narayana  
Capstone Project – Deep Learning Summer School, 2025
