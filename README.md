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
  
## 🖥️ Running the Project
Run the notebook directly in Google Colab for GPU acceleration
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1IPXs9Qjggbm7MqANjipcpEJZdVOlC9qe?usp=sharing)
