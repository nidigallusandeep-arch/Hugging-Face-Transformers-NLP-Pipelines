# 🤗 Hugging Face Transformers and Pipelines

## 📌 Project Overview
This project focuses on learning and exploring **Hugging Face Transformers** and **Pipeline API** for Natural Language Processing (NLP) and Computer Vision tasks.

Hugging Face provides pre-trained models that make it easy to perform different AI tasks without training models from scratch.

## 🎯 Objectives
- Understand Hugging Face Transformers.
- Learn how to use the Pipeline API.
- Work with pre-trained models.
- Perform text generation and sentiment analysis.
- Explore fill-mask and feature extraction.
- Understand object detection using Transformers.

## 🛠️ Technologies Used
- Python
- Hugging Face Transformers
- PyTorch
- PIL (Pillow)
- Matplotlib
- Google Colab
- Jupyter Notebook

## 📂 Project Structure

```text
Hugging-Face-Transformers-and-Pipelines/
│
├── Intro_to_HuggingFace.ipynb
├── Pipeline.ipynb
└── README.md
```

## 📚 Topics Covered

### 1. Introduction to Hugging Face
- Introduction to Hugging Face
- Transformers Library
- Pre-trained Models
- Tokenization
- NLP Concepts

### 2. Hugging Face Pipelines
- Text Generation
- Sentiment Analysis
- Fill-Mask
- Feature Extraction
- Object Detection

## 💻 Installation

```bash
pip install transformers
pip install torch
pip install pillow
pip install matplotlib
```

## 🚀 Basic Example

```python
from transformers import pipeline

generator = pipeline(
    "text-generation",
    model="gpt2"
)

prompt = "Artificial Intelligence will"

output = generator(
    prompt,
    max_new_tokens=50,
    num_return_sequences=1
)

print(output[0]["generated_text"])
```

## 📊 Applications
- Natural Language Processing
- Text Generation
- Sentiment Analysis
- Language Understanding
- Computer Vision
- Object Detection

## 🎓 Learning Outcome

Through this project, I learned how to use Hugging Face pre-trained models and pipelines to perform different NLP and AI tasks.

GitHub: [My GitHub Profile](https://github.com/)

---

⭐ If you find this project useful, please give it a star!
