# Fraud-Synthesizer

![GAN Illustration](gan_image.png)

---

## 📖 Overview  
Fraudulent transactions are **rare, sensitive, and difficult to collect** — making fraud detection a huge challenge in finance & banking.

This project uses **Generative Adversarial Networks (GANs)** 🤖 to generate realistic **synthetic fraud transactions** while preserving important patterns from real data.

👉 The generated synthetic data can help expand fraud datasets and improve the training and evaluation of fraud detection models.
---

## 📊 Dataset  
We used the **[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/sowmyakuruba/credit-card-fraud-detection/data)** from Kaggle.  
- File included: `Creditcard_dataset.csv`  

---

## 🎯 Motivation  
- Fraud data is **highly imbalanced** (fraud cases are extremely rare).  
- GANs can **augment data** by generating realistic fraud samples.  
- Helps build **robust fraud detection models** with better generalization.  

---

## ⚙️ Requirements  
Make sure you have the following dependencies installed:  

```bash
Python >= 3.7
TensorFlow
Keras
NumPy
Pandas
Matplotlib
Scikit-learn
XGBoost
