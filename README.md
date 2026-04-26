# 📩 Spam Detection using Machine Learning

## 🚀 Overview

This project builds a Machine Learning model to classify messages as **Spam** or **Not Spam (Ham)**.
It demonstrates a complete ML workflow including **text preprocessing, feature extraction, model training, and evaluation**.

---

## 🎯 Problem Statement

With the increasing number of unwanted messages, it is important to automatically detect spam.
The goal of this project is to classify text messages into:

* **Spam (1)**
* **Not Spam / Ham (0)**

---

## 🧠 Approach

### 1. Data Preprocessing

* Cleaned text data
* Removed unnecessary characters
* Converted text into numerical format

---

### 2. Feature Extraction

Used:

* **CountVectorizer** (Bag of Words)
* **TF-IDF Vectorizer** (improved feature weighting)

---

### 3. Models Used

* Naive Bayes (MultinomialNB)
* Logistic Regression

---

### 4. Evaluation Metrics

* Accuracy Score
* Model comparison

---

## 📊 Results

* Naive Bayes performed efficiently for text classification
* TF-IDF improved feature representation and model performance

---

## 🛠️ Tech Stack

* Python
* Pandas
* scikit-learn
* NumPy

---

## 📁 Project Structure

```bash
spam-detection/
│── model.ipynb
│── data.csv
│── README.md
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/spam-detection.git
```

2. Navigate to the project:

```bash
cd spam-detection
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the notebook:

```bash
jupyter notebook
```

---

## 🧪 Example

Input:

```
"Congratulations! You won a free prize"
```

Output:

```
Spam
```

---

## 📈 Future Improvements

* Use larger real-world datasets
* Try advanced models (Random Forest, Boosting)
* Apply Deep Learning using TensorFlow

---

## 💡 Key Learnings

* Text data must be converted into numerical features
* Naive Bayes works well for probabilistic text classification
* Feature engineering (TF-IDF) improves performance

---

## 👨‍💻 Author

Priyanshu Gupta
GitHub: https://github.com/priyanshugupta233

---

