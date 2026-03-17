# 📧 Email Spam Classifier

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![ML](https://img.shields.io/badge/ML-Scikit--Learn-orange)
![Notebook](https://img.shields.io/badge/Notebook-Jupyter-blue)

---

## 🚀 Project Overview

A Machine Learning-based Email Spam Classifier that detects whether an email/message is **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries Used:**

  * pandas
  * numpy
  * scikit-learn
  * nltk
  * matplotlib
  * seaborn

---

## 📂 Project Structure

```
.
├── Email_Spam_Classifier.ipynb   # Jupyter Notebook with implementation
├── spam.csv                      # Dataset
└── README.md                     # Documentation
```

---

## 📊 Dataset

* Contains labeled messages:

  * **Spam**
  * **Ham (Not Spam)**

**Columns:**

* `label` → spam/ham
* `message` → text content

---

## 🔄 Workflow

1. **Data Loading**

2. **Text Preprocessing**

   * Lowercasing
   * Removing punctuation
   * Stopword removal
   * Tokenization

3. **Feature Extraction**

   * Bag of Words / TF-IDF

4. **Model Training**

   * Naive Bayes
   * Logistic Regression
   * Decision Tree

5. **Model Evaluation**

   * Accuracy Score
   * Confusion Matrix
   * Precision & Recall

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Hansder01/https://github.com/Hansder01/Email-Spam-Classifier
cd Email-Spam-Classifier
```

### 2. Run the Notebook

```bash
jupyter notebook
```

---

## 📦 requirements.txt

```
pandas
numpy
scikit-learn
nltk
matplotlib
seaborn
```

---

## 📈 Sample Output

* **Input:** `"Congratulations! You have won a lottery"`
  → **Output:** `Spam`

* **Input:** `"Let's meet tomorrow for the project"`
  → **Output:** `Ham`

---

## 💡 Key Features

* End-to-end NLP pipeline
* Clean and modular implementation
* Real-world dataset usage
* Easily extendable to deep learning models

---

## 🔮 Future Enhancements

* Deploy using **Streamlit / Flask**
* Add deep learning models (LSTM, BERT)
* Hyperparameter tuning
* Real-time spam detection system

---

## 👨‍💻 Author

**Sayan Bhanja Chowdhury**
Aspiring Data Professional | Machine Learning Enthusiast

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⚠️ Final Notes

Before uploading to GitHub:

* Replace `your-username/email-spam-classifier` with your actual repo link
* Update **Accuracy (97%)** with your real model result

---

If you want, I can next:

* Add **live demo (Streamlit) badge + deployment guide**
* Create a **portfolio-level README with visuals and diagrams**
* Convert this into a **LinkedIn project post** 🚀
