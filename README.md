# 🧠 NLP Sentiment Analysis using NLTK, TF-IDF & Logistic Regression

## 📌 Project Overview

This project implements an end-to-end **Natural Language Processing (NLP)** pipeline to classify textual data into sentiment categories using **Machine Learning** techniques.

The workflow includes text preprocessing with **NLTK**, feature extraction using **TF-IDF Vectorization**, model training with **Logistic Regression**, performance evaluation using classification metrics, and visualization through **WordCloud** and sentiment distribution charts.

The trained model and TF-IDF vectorizer are also saved for future inference without retraining.

---

## 🎯 Objective

The objective of this project is to:

- Perform sentiment analysis on textual data.
- Clean and preprocess raw text using NLP techniques.
- Convert text into numerical features using TF-IDF.
- Train a machine learning classifier for sentiment prediction.
- Evaluate model performance using standard classification metrics.
- Save the trained model for future predictions.

---

# 🛠️ Technologies Used

| Category | Tools |
|----------|-------|
| Programming Language | Python |
| NLP | NLTK |
| Machine Learning | Scikit-learn |
| Feature Extraction | TF-IDF Vectorizer |
| Model | Logistic Regression |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, WordCloud |
| Model Persistence | Joblib |
| Development Environment | Jupyter Notebook |

---

# 📂 Project Structure

```
Sentiment-Analysis/
│
├── sentiment_analysis.ipynb          # Complete notebook
├── sentiment_dataset.csv             # Original dataset
├── sentiment_model.pkl               # Trained Logistic Regression model
├── tfidf_vectorizer.pkl              # Saved TF-IDF vectorizer
├── positive_wordcloud.png            # WordCloud visualization
├── sentiment_distribution.png        # Sentiment distribution chart
├── confusion_matrix.png              # Confusion Matrix
├── requirements.txt                  # Required libraries
└── README.md
```

---

# 🔄 Project Workflow

```
Dataset
   │
   ▼
Load Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Text Preprocessing (NLTK)
   │
   ├── Lowercase Conversion
   ├── Tokenization
   ├── Stopword Removal
   ├── Punctuation Removal
   └── Text Cleaning
   │
   ▼
TF-IDF Vectorization
   │
   ▼
Train-Test Split
   │
   ▼
Logistic Regression Model
   │
   ▼
Prediction
   │
   ▼
Model Evaluation
   │
   ├── Accuracy
   ├── Precision
   ├── Recall
   ├── F1-Score
   └── Confusion Matrix
   │
   ▼
Visualization
   │
   ├── WordCloud
   └── Sentiment Distribution
   │
   ▼
Save Model (.pkl)
```

---

# 📖 Dataset

The project uses a labeled text dataset containing textual samples with their corresponding sentiment labels.

Typical labels include:

- Positive
- Negative
- Neutral *(if available in the dataset)*

---

# 🧹 Text Preprocessing

The following preprocessing techniques were applied using **NLTK**:

- Convert text to lowercase
- Tokenization
- Remove stopwords
- Remove punctuation
- Remove non-alphabetic words
- Clean text for feature extraction

---

# 📊 Feature Engineering

The cleaned text is transformed into numerical vectors using:

- **TF-IDF (Term Frequency-Inverse Document Frequency)**

This technique converts textual information into machine-readable numerical features while preserving the importance of words.

---

# 🤖 Machine Learning Model

The project uses:

**Logistic Regression**

Reasons for selection:

- Efficient baseline classifier for text classification
- Fast training and prediction
- Performs well with sparse TF-IDF features
- Interpretable model for binary and multiclass classification

---

# 📈 Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

These metrics provide a comprehensive understanding of the classifier's performance.

---

# 📊 Visualizations

The project includes:

- 📌 Sentiment Distribution Chart
- ☁️ WordCloud Visualization
- 📉 Confusion Matrix

These visualizations help understand class distribution, frequent terms, and prediction performance.

---

# 💾 Model Persistence

To avoid retraining every time, the following artifacts are saved:

- `sentiment_model.pkl`
- `tfidf_vectorizer.pkl`

These files can be loaded later to predict sentiment for new text inputs.

---

# 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Sentiment-Analysis.git
```

### 2. Navigate to the project

```bash
cd Sentiment-Analysis
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
sentiment_analysis.ipynb
```

Run all cells sequentially.

---

# 📌 Sample Prediction

**Input**

```
I absolutely love this product.
```

**Predicted Sentiment**

```
Positive
```

---

# 📚 Key Learning Outcomes

Through this project, I gained practical experience in:

- Natural Language Processing (NLP)
- Text preprocessing using NLTK
- TF-IDF feature extraction
- Machine Learning for text classification
- Logistic Regression
- Model evaluation techniques
- Data visualization
- Model serialization using Joblib
- End-to-end machine learning workflow

---

# 🔮 Future Improvements

Possible enhancements include:

- Lemmatization and stemming
- Hyperparameter tuning
- Testing advanced models (Naive Bayes, SVM, Random Forest)
- Deep Learning approaches (LSTM/BERT)
- Streamlit or Flask deployment
- REST API integration using FastAPI

---

# 👩‍💻 Author

**Samiksha Hujare**

Computer Science Engineering Student

Interested in:

- Data Science
- Machine Learning
- Artificial Intelligence
- Natural Language Processing

---

## ⭐ If you found this project useful, consider giving it a Star!
