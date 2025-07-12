# Emotion Detection Chatbot 🤖💬

This project is an emotion-aware chatbot that detects user emotions and generates empathetic responses using a mix of ensemble models and LLMs.

 Emotion-Aware Chatbot with LLaMA, Flan-T5 & Ensemble Classification

This project implements an emotion-aware chatbot that:
- Detects user emotions using an ensemble of transformers (RoBERTa, T5).
- Rephrases long messages using BART or FLAN-T5.
- Generates empathetic responses using TinyLLaMA with fallbacks.
- Uses rule-based templates and validation to ensure relevant replies.

> 📄 Full documentation with flowcharts and design: See `docs/emotion detection.pdf`

## 📁 Files

- `notebook.ipynb`: Main Kaggle implementation.
- `documentation.pdf`: Project summary.
- `result/`: Sample user messages and results.
- `README.md`: This file.

## 📦 Input Dataset

### Dataset
We used the [dair-ai/emotion](https://huggingface.co/datasets/dair-ai/emotion) dataset from Hugging Face:
- 6 emotion classes: joy, sadness, anger, fear, surprise, love
- Used ensemble models (Multilingual MiniLM + RoBERTa) for robust emotion classification.


## ⚙️ Limitations

- TinyLLaMA's generative quality is limited on local machine.
- Kaggle used due to local hardware constraints.

## 📈 Future Work

- Add better LLM (Zephyr, GPT-3.5).
- Integrate Retrieval-Augmented Generation (RAG) for personalized responses.

---
