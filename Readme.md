# 🧠 AI Projects: Off-label Drug Recommender & Grocery Image Classifier

This repository contains two AI-powered projects created using Google Colab:

1. **Off-label Drug Recommender** – Uses Google Gemini API to suggest alternative or off-label uses of drugs based on clinical context.
2. **Grocery Store Image Classifier** – An image classification system to identify grocery store items using deep learning.

---

## 📁 Contents

- `off_label_drug_recommender.ipynb`  
  A clinical NLP assistant that uses large language models (Gemini 1.5 Pro or 2.5 Pro) to analyze a given symptom/disease description and recommend possible off-label drug uses based on a local drug database.

- `Grocery_store_image_search_classificationV2.ipynb`  
  A vision-based model that classifies grocery items using deep learning and computer vision techniques. Trained and tested on image datasets of common grocery products.

---

## 🧪 Technologies Used

- Python 3
- Google Colab
- pandas, requests, json
- Google Generative AI SDK (`google.generativeai`)
- TensorFlow / PyTorch (used in image classification notebook)
- Gemini Pro API (v1 endpoint)

---

## ⚕️ Off-label Drug Recommender Highlights

- Queries a structured local CSV database of drugs and their approved uses
- Matches drugs relevant to a given clinical symptom
- Sends targeted prompts to Gemini Pro models via `generate_content`
- Outputs concise, pharmacologically sound suggestions

✅ Rate-limited to avoid API quota overuse  
✅ Designed for clinical/pharma research and experimentation (not real-world diagnosis)

---

## 🛒 Grocery Store Image Classifier Highlights

- Uses a CNN (Convolutional Neural Network) or pretrained model for grocery image recognition
- Data augmentation and preprocessing included
- Suitable for retail automation, inventory management, or smart cart solutions

---

## 🚀 Getting Started

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
