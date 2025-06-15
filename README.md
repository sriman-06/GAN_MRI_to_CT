# GAN for MRI to CT Image Translation 🧠➡️🦴

This project uses a **Pix2Pix GAN** architecture to convert brain MRI images to CT scans using the **SynthRAD2023** dataset. It was developed as part of a Deep Learning Summer School Capstone Project.

## 📝 Notebook
- `GAN_FOR_MRI_TO_CT(image_resolution).ipynb` – Main Colab notebook with preprocessing, training, and testing.

## 🧠 Dataset
- **SynthRAD2023** – Rigidly aligned MRI and CT pairs  
  📎 [Zenodo Dataset Link](https://zenodo.org/record/8268565)

## 🧰 Architecture
- Generator: U-Net (as in Pix2Pix)
- Discriminator: PatchGAN
- Loss: L1 + Adversarial (GAN) Loss

## 📊 Evaluation Metrics (on Subject 1BB028)
- **Mean SSIM:** 0.86  
- **PSNR:** 22.5 dB  

## 🖼️ Sample Outputs
*(Include a few sample before/after images in future)*

## 🚀 How to Run
1. Open the notebook in **Google Colab**
2. Upload SynthRAD2023 images to `/content/data/`
3. Run training cells
4. Visualize generated CTs from MRI

## 📁 Future Work
- Add SSIM loss
- Try CycleGAN or MedGAN variants
- Deploy as web app using Gradio or Streamlit

## 🙋‍♂️ Author
Sriman Narayana  
Capstone Project | Deep Learning Summer School, 2025

---
