# 📧 Email Spam Detection with Naive Bayes

This is a simple machine learning project that uses the Naive Bayes algorithm and CountVectorizer to classify emails as **spam** or **ham** (not spam).

---

## 📂 Dataset

Make sure to include `spam_ham_dataset.csv` in the `data/` folder. It should contain at least these columns:

- `text` — the email message
- `label_num` — target label (`0 = ham`, `1 = spam`)

---

## 🧠 Model Pipeline

1. Load and explore the dataset
2. Preprocess the text using **Bag of Words** (`CountVectorizer`)
3. Train a **Multinomial Naive Bayes** classifier
4. Evaluate the model on test data
5. Print accuracy and classification report

---

## ▶️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/SubhanAli-creator/email-spam-detector
cd email-spam-detector
