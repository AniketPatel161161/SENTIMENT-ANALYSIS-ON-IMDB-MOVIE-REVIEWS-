# SENTIMENT-ANALYSIS-ON-IMDB-MOVIE-REVIEWS-
# 🎬 RNN Sentiment Analysis

A simple **Sentiment Analysis** project using **NLP and Recurrent Neural Networks (RNN)** with the **IMDB Movie Reviews dataset**.

## 📌 About the Project

The model classifies movie reviews into:

* 😊 **Positive**
* 😞 **Negative**

The project covers the complete NLP pipeline from text preprocessing to model evaluation.

## 🔄 Workflow

```text
IMDB Dataset
     ↓
Text Preprocessing
     ↓
Tokenization & Stopword Removal
     ↓
Stemming
     ↓
TF-IDF Vectorization
     ↓
Train/Test Split
     ↓
RNN Model
     ↓
Prediction & Evaluation
```

## 🛠️ Technologies Used

* 🐍 Python
* 🧠 PyTorch
* 📝 NLTK
* 📊 Pandas
* 🔢 Scikit-learn
* 📓 Jupyter Notebook

## 🧹 Text Preprocessing

The reviews are processed using:

* Lowercase conversion
* HTML & URL removal
* Punctuation removal
* Stopword removal
* **Porter Stemming**

## 🤖 Model

The project uses a **PyTorch RNN** with:

* TF-IDF input features
* Hidden size: **128**
* 1 RNN layer
* Adam optimizer
* Binary Cross Entropy loss
* **10 epochs**

## 📈 Evaluation

The model predicts whether a review is **Positive or Negative** using a probability threshold of **0.5** and evaluates performance using classification accuracy.

## 🚀 How to Run

```bash
pip install pandas nltk scikit-learn torch jupyter
```

Then open:

```text
RNN_SENTIMENTanalysis.ipynb
```

and run the cells sequentially.

## 📁 Project Structure

```text
RNN-Sentiment-Analysis/
│
├── RNN_SENTIMENTanalysis.ipynb
├── IMDB Dataset.csv
└── README.md
```

## 👨‍💻 Author

**Aniket Patel**
Computer Science Honours
