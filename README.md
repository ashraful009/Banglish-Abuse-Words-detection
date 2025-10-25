# 🧠 Banglish Abuse Words Detection and Classification

This project focuses on detecting and classifying **abusive or hate speech** in **Banglish (Bangla–English mixed)** text.  
It aims to identify whether a given Banglish sentence contains hate speech, and determine the **type of abusive content** it represents.

---

## 🔍 Task Overview

### Input:
A Banglish sentence (Bangla + English mixed text)

### Output:
1. **Binary Classification:** Detect whether the sentence contains hate speech (`Yes` / `No`)
2. **Multiclass Classification:** If hateful, predict the specific abuse category

---

## 🎯 Classes

The dataset includes **7 categories** of Banglish text:

| Label | Description |
|--------|--------------|
| Others | General or neutral content |
| Sexual | Sexually explicit or abusive content |
| Slang | Use of offensive or vulgar slang |
| Not Hate | Normal / non-abusive text |
| Racial | Race or ethnicity-based hate speech |
| Religious | Religion-based hate speech |
| Appearance | Abuse targeting someone’s physical appearance |

---

## ⚙️ Approach

The model is trained on a **Banglish hate speech dataset** that contains mixed Bangla-English sentences collected from social platforms and user-generated content.  
It uses **Natural Language Processing (NLP)** and **Deep Learning** techniques to handle code-mixed language structure.

### 🔧 Key Steps
- **Text Preprocessing:** Tokenization, punctuation removal, transliteration handling  
- **Feature Extraction:** TF-IDF and Transformer embeddings  
- **Modeling:** Machine Learning, Deep Learning, and Transformer-based models  
- **Evaluation:** Accuracy, F1-score, and Confusion Matrix  

---

## 📦 Technologies Used

- Python  
- Scikit-learn  
- TensorFlow / PyTorch  
- Transformers (HuggingFace)  
- Pandas, NumPy, Matplotlib  

---

## 🚀 Applications

- Automatic moderation of online content  
- Detection of hate speech in Bangladeshi social media platforms  
- Research on **low-resource and code-mixed languages**  

---

## 📊 Results (Example)

| Metric | Binary Classification | Multiclass Classification |
|--------|------------------------|----------------------------|
| Accuracy | 0.00 | 0.00 |
| F1-score | 0.00 | 0.00 |



## 📄 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

**Md Ashraful Islam**  
📍 Dhaka, Bangladesh  
🔗 [GitHub Profile](https://github.com/ashraful009)

---

