
# 🌍 English–Hindi Neural Machine Translation (NMT)

A deep learning–based Neural Machine Translation (NMT) system that translates English → Hindi using a Transformer model implemented from scratch.

This project demonstrates how self-attention mechanisms and encoder–decoder architectures power modern language translation systems.


---

## 🚀 Open in Google Colab

Click below to run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1uzOw7-mvqn_8Fd5CqNl9VZztKd15tLY4?usp=sharing)


---

## 📌 Project Overview

This project builds an **end-to-end Machine Translation system** using the Transformer model (Attention Is All You Need).

The notebook includes:

- Data preprocessing for bilingual text  
- Tokenization & vocabulary building  
- Positional Encoding  
- Transformer Encoder–Decoder architecture  
- Model training and evaluation  
- English → Hindi inference generation  

---

## 🧠 Model Architecture

The system is based on the **Transformer architecture**.

### Main Components:

- Encoder (Multi-Head Self-Attention + Feed Forward Network)
- Decoder (Masked Attention + Encoder–Decoder Attention)
- Positional Encoding
- Embedding Layers
- Linear + Softmax Output Layer

---

---

## 📊 Dataset

This project uses the **IIT Bombay English–Hindi Parallel Corpus**, a widely used dataset for machine translation research. It contains aligned English–Hindi sentence pairs for supervised sequence-to-sequence learning.

 **Dataset Source:**  
[IITB English–Hindi Dataset on Hugging Face](https://huggingface.co/datasets/cfilt/iitb-english-hindi)

------

## ⚙️ Tech Stack

- Python  
- TensorFlow / PyTorch (Update based on your implementation)
- NumPy  
- Pandas  
- Matplotlib  
- NLP preprocessing tools  

---

## 📂 Project Structure

```text

English-Hindi-NMT/
│
├── Dataset                  # English–Hindi parallel text dataset
├── vocab_itb.json           # Vocabulary  token-to-index mapping file
├── English–Hindi.ipynb      # Transformer model implementation notebook
└── README.md #               

```

## 🔄 Workflow

### 1️⃣ Load Dataset
- Parallel English–Hindi sentence pairs

### 2️⃣ Preprocessing
- Text cleaning  
- Tokenization  
- Padding sequences  
- Vocabulary creation  

### 3️⃣ Model Building
- Embedding Layer  
- Positional Encoding  
- Transformer Encoder  
- Transformer Decoder  

### 4️⃣ Training
- Loss Function: Cross-Entropy  
- Optimizer: Adam  
- Teacher Forcing (if implemented)  

### 5️⃣ Evaluation
- Sample translations  
- Performance observation  

---

## 📊 Sample Results

[](pictures/Screenshot 2026-03-22 122319.png)

---

## 🎯 Applications

- 🌐 Machine Translation Systems  
- 🤖 Multilingual Chatbots  
- 📚 Educational Tools  
- 🔬 NLP Research  

---

## 📚 Key Concepts Used

- Transformer Architecture  
- Self-Attention Mechanism  
- Sequence-to-Sequence Learning  
- Positional Encoding  
- Tokenization  

---

## 👤 Author

**Rohit Sahu**  
Machine Learning & NLP Enthusiast  

📧 Email: quantumsolitaryseeker@gmail.com  

🔗 LinkedIn: https://www.linkedin.com/in/rohit-sahu-7142742a7/

🐙 GitHub: https://github.com/Solitaryseeker

---

⭐ If you found this project helpful, consider giving it a star!
