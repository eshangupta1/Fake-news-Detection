# 📰 Fake News Detection using NLP and Machine Learning

This project detects fake news articles using Natural Language Processing (NLP) and Machine Learning techniques. It uses TF-IDF vectorization and Logistic Regression to classify whether a news article is **real or fake**. The pipeline includes text cleaning, model training, evaluation, and future deployment scope.

---

## ✅ Key Features
- Built a **binary classification model** to distinguish fake news from real news articles.
- Implemented **TF-IDF vectorization** for feature extraction from textual data.
- Trained and evaluated **Logistic Regression**, achieving over **94% accuracy**.
- Includes detailed performance evaluation using **Precision, Recall, F1-score**, and **Confusion Matrix**.
- Modular structure, easily extendable to include **Naive Bayes**, **Random Forest**, or **SHAP explainability**.

---

## 📁 Dataset
- **Source**: [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
- **Total Samples**: ~20,000
- **Features**: News Title, Article Text, Label (REAL/FAKE)

---

## 🧪 Model Performance
| Model               | Accuracy |
|--------------------|---------- |
| Logistic Regression| 99.4%     |
| (Optional) Naive Bayes | TBD   |
| (Optional) Random Forest | TBD |

> 📌 Classification report and confusion matrix are shown in the notebook.

---

## ⚙️ Tech Stack
- **Language**: Python
- **Libraries**: `sklearn`, `nltk`, `pandas`, `numpy`, `seaborn`, `matplotlib`
- **Platform**: Google Colab

---

## ▶️ How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Run the cells in sequence — data will be loaded and preprocessed.
3. The model will be trained and evaluated.
4. (Optional) Add a `Gradio` interface for real-time prediction.

---

## 📦 Folder Structure
