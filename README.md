# Emotion Classification with DistilBERT

A compact, high-signal NLP project that fine-tunes **DistilBERT** to classify text into **six emotions** using the **dair-ai/emotion** dataset.

## What This Project Does
- **Loads + preprocesses** the emotion dataset  
- **Fine-tunes DistilBERT** for multi-class emotion classification  
- **Evaluates performance** with **Accuracy**, **Weighted F1**, and **per-class metrics**  
- **Visualizes mistakes** with a **confusion matrix**

## Dataset
- **Dataset:** dair-ai/emotion  
- **Labels (6):** sadness, joy, love, anger, fear, surprise  
- **Splits:**  
  - **Train:** 16k  
  - **Validation:** 2k  
  - **Test:** 2k  

## Model
- **Base model:** distilbert-base-uncased  
- **Tokenization:** Hugging Face  
- **Training:** Trainer API  
- **Model selection:** best checkpoint chosen by **Weighted F1**

## Results
- **Accuracy:** ~0.92  
- **Weighted F1:** ~0.92  
- **Note:** strong performance overall; **surprise** is typically the hardest class to predict.

## Tools Used
- Python  
- PyTorch  
- Hugging Face Transformers + Datasets  
- Scikit-learn  
- Matplotlib / Seaborn  

## References
- Dataset: dair-ai/emotion  
- Model: distilbert-base-uncased  
- Hugging Face Transformers docs  
