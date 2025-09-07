# 🩺 MedGemma Diagnostic Assistant

A multimodal AI-powered assistant that uses Google’s **MedGemma 4B** model to analyze medical images and text prompts for diagnostic insights. This project demonstrates how vision and language can work together to assist in general medical image understanding.

## 🚀 Features
- Accepts both **medical images** (X-ray, skin scans, fractures, etc.) and **text prompts**
- Generates human-like diagnostic responses
- Built with Hugging Face's Transformers and Google’s MedGemma model
- Runs on **Google Colab with GPU support**
  
## 🧠 Model Used
- [`google/medgemma-4b-it`](https://huggingface.co/google/medgemma-4b-it)
  
## 📦 Dependencies
- `transformers`
- `accelerate`
- `bitsandbytes`
- `gradio`
- `torch`
- `PIL`

  ## 📹 Project Demo
[Watch the demo video on Google Drive](https://drive.google.com/file/d/1HBQHAJfq8Ypghj24PLaZ3o5S4vCiN8J0/view?usp=sharing)

## ⚠️ Data Privacy & Usage Disclaimer

This project is intended for **research and educational purposes only**.

Please **DO NOT upload any real, identifiable, or sensitive patient data** (such as actual X-ray, CT, or MRI scans containing personal information) to the Google Colab notebook or any public cloud environment linked to this repository.

If you choose to test the model, ensure that:

- The medical images are **fully anonymized**
- No **personally identifiable information (PII)** is present in the image or its metadata
- You are in full compliance with your region's data protection regulations  
  _(e.g., **DPDPA 2023** in India, **HIPAA** in the U.S., or **GDPR** in the EU)_

---

By using this repository, you acknowledge that:

- The developer does **not collect, store, or process any user-uploaded data**
- Any testing performed on clinical data is **entirely at the user's discretion and risk**
- For clinical or pilot deployments, it is strongly recommended to use a  
  **secure, in-house server** or **DPDPA-compliant infrastructure**


  
## 🖥️ Running the Project
Run the notebook directly in Google Colab for GPU acceleration
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1IPXs9Qjggbm7MqANjipcpEJZdVOlC9qe?usp=sharing)
