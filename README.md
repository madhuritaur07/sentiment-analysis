# Sentiment Analysis using Machine Learning and Streamlit

## Project Overview

This project is a Sentiment Analysis application that predicts the sentiment of a given text using Machine Learning techniques. The model is trained on text data and deployed through a user-friendly Streamlit web interface.

The application allows users to enter text and instantly receive the predicted sentiment.

---

# Features

* Text preprocessing and cleaning
* TF-IDF feature extraction
* Logistic Regression classifier
* Real-time sentiment prediction
* Interactive Streamlit web interface

---

# Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Joblib
* Streamlit

---

# Project Structure

```text
sentiment-analysis/
│
├── train_model.py
├── app.py
├── sentiment.csv
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
└── README.md
```

---

# Dataset

The dataset contains text samples and their corresponding sentiment labels.

Example:

| Text                 | Sentiment |
| -------------------- | --------- |
| This game is amazing | Positive  |
| I am disappointed    | Negative  |

---

# Model Training

Run the training script:

```bash
python train_model.py
```

This will:

* Load the dataset
* Clean and preprocess text
* Convert text using TF-IDF
* Train the Logistic Regression model
* Save the trained model and vectorizer

Generated files:

```text
model.pkl
vectorizer.pkl
```

---

# Running the Streamlit Application

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

The application will open automatically in your browser.

Default URL:

```text
http://localhost:8501
```

---

# Example Usage

Input:

```text
This game is amazing and fun to play
```

Output:

```text
Predicted Sentiment: Positive
```

Input:

```text
I am very unhappy with this product
```

Output:

```text
Predicted Sentiment: Negative
```

---

# Machine Learning Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Text Preprocessing
   ↓
TF-IDF Vectorization
   ↓
Train-Test Split
   ↓
Logistic Regression Model
   ↓
Model Evaluation
   ↓
Save Model
   ↓
Streamlit Deployment
```

---

# Evaluation Metrics

The model is evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

# Future Improvements

* Use advanced NLP models such as BERT
* Add sentiment confidence scores
* Deploy on cloud platforms
* Support multiple languages

---

# Author

Madhuri Taur

Machine Learning Project – Sentiment Analysis using Streamlit
