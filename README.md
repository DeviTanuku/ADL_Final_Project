# 💬 Yelp Sentiment Classification using LSTM and DistilBERT

> 🎓 **Course:** AIGC5005 – Advanced Deep Learning  
> 📘 **Project Type:** Final Project  
> 👥 **Team Members:** Chandana, Devi, Jaspreet  
> 🌐 **Domain:** Natural Language Processing (NLP)  
> 🧠 **Task:** Multiclass Sentiment Classification – *Positive, Negative, Neutral*

---

## 📌 Project Overview

This project compares two deep learning models—**LSTM** and **DistilBERT**—to classify sentiment in Yelp hospitality reviews. The goal is to label reviews as **Positive**, **Negative**, or **Neutral**, and assess how each model performs across text lengths and domain-specific language.

We evaluate both models using standard NLP metrics and interpretability tools to understand not just what they predict, but why.

---

## 🎯 Objectives

- ✅ Build a cleaned and balanced dataset from Yelp reviews.
- ✅ Train an LSTM model using word embeddings.
- ✅ Fine-tune a pre-trained DistilBERT transformer model.
- ✅ Evaluate models using metrics: *Accuracy, Precision, Recall, F1-Score*.
- ✅ Analyze model predictions using **SHAP** and **LIME**.
- ✅ Apply hyperparameter tuning for optimal performance.

---

## 🗂️ Project Structure

ADL_Final_Project/ ├── data/ # Preprocessed Yelp dataset ├── notebooks/ # Jupyter Notebooks │ ├── 1_LSTM_Model.ipynb # LSTM model implementation │ ├── 2_DistilBERT_Model.ipynb # DistilBERT fine-tuning ├── outputs/ # Model outputs and logs │ ├── plots/ # Training plots, SHAP, and LIME visuals │ └── training_logs/ # Loss/accuracy tracking ├── saved_models/ # Best model checkpoints │ ├── best_model_lstm/ # Trained LSTM model │ └── best_model_distilbert/ # Trained DistilBERT model ├── report/ # Final academic report │ └── AIGC5005_Final_Report.pdf ├── requirements.txt # Python package dependencies └── README.md # Project overview (this file)
