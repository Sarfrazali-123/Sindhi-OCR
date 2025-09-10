# Sindhi OCR using Tesseract 5 + LSTM

This project is an **Optical Character Recognition (OCR) system for Sindhi**, developed by fine-tuning a pretrained model from **Tesseract 5** using its **LSTM architecture**.

## 📌 Features
- Supports Sindhi script recognition
- Built on Tesseract 5 OCR engine
- Uses LSTM for sequence-based text recognition
- Trained on **10,000 images** with corresponding ground-truth text files

## 🛠️ Tech Stack
- [Tesseract OCR 5](https://github.com/tesseract-ocr/tesseract)
- LSTM Neural Networks
- Python

## 📂 Dataset
- **10,000 image-text pairs**
- Each image contains Sindhi text
- Each `.txt` file contains the corresponding ground-truth transcription

## 🚀 Training Process
1. Prepared dataset (images + text pairs).
2. Fine-tuned pretrained Tesseract 5 model.
3. Used LSTM training for sequence learning.
4. Evaluated accuracy on Sindhi text.

## 📊 Results
- Improved accuracy for Sindhi OCR
- Successfully recognizes Sindhi characters and words

## 📖 Usage
1. Install Tesseract 5:
   ```bash
   sudo apt install tesseract-ocr
