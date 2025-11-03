# AICourseProject
# 💬 Exploring Explainability in Sentiment Classification Models Using LIME and SHAP

This project explores **explainable artificial intelligence (XAI)** techniques for **sentiment classification** using the **DistilBERT transformer model**.  
The goal is to understand *why* a model makes certain predictions by visualizing token-level contributions using **LIME** (Local Interpretable Model-agnostic Explanations) and **SHAP** (SHapley Additive exPlanations).

---

##  Objective

While transformer-based models like BERT and DistilBERT achieve high accuracy, they often behave as **black boxes**.  
This project focuses on bridging that gap by:

- Training a **DistilBERT** sentiment classifier on labeled text data.  
- Evaluating performance using **Accuracy, Precision, Recall, and F1-score**.  
- Applying **LIME** and **SHAP** to interpret predictions and highlight influential words.  

---

##  Repository Structure

| File | Description |
|------|--------------|
| `01_load_and_preprocess.ipynb` | Loads and cleans the sentiment dataset, performs tokenization using DistilBERT tokenizer, and prepares train/validation splits. |
| `02_train_distilbert.ipynb` | Fine-tunes the DistilBERT model for sentiment classification and computes evaluation metrics — Accuracy, Precision, Recall, and F1. |
| `03_explainability.ipynb` | Uses **LIME** and **SHAP** explainers to visualize model predictions and identify key tokens driving sentiment decisions. |

---

