# 🧠 Sentiment Analysis on Twitter & Reddit Data

This project performs sentiment analysis on Twitter and Reddit datasets using Natural Language Processing (NLP) and machine learning techniques. The model classifies sentiment into categories and applies the trained model on both datasets.

---

## 📁 Dataset

- `Twitter_Data.csv`: Contains tweets and their sentiment categories.
- `Reddit_Data.csv`: Contains Reddit comments and their sentiment categories.

---

## 🚀 Project Pipeline

### ✅ Step 1: Import Libraries
- Includes essential libraries for data analysis, visualization, NLP, and modeling.

### 📥 Step 2: Load Data
- Loads Twitter and Reddit CSV files using pandas.

### 👁️ Step 3: Exploratory Data Analysis (EDA)
- Displays dataset info and visualizes sentiment distribution using seaborn.

### 🧹 Step 4: Preprocessing
- Cleans text (lowercasing, removing URLs, punctuation, digits).
- Applies lemmatization and removes stopwords using NLTK.

### 🧪 Step 5: Feature Extraction
- Converts cleaned text into numerical features using TF-IDF Vectorization.

### 🧩 Step 6: Train/Test Split
- Splits Twitter data into training and test sets using stratified sampling.

### 🤖 Step 7: Model Training
- Trains a Logistic Regression model on the Twitter dataset.

### 📊 Step 8: Model Evaluation
- Evaluates the model using classification report, accuracy score, and confusion matrix.

### 📈 Step 9: Predict Sentiment on Reddit
- Applies the trained model to predict sentiment of Reddit comments and visualizes the prediction distribution.

### 💾 Step 10: Save Model & Vectorizer
- Saves the trained Logistic Regression model and TF-IDF vectorizer using `joblib`.

---

## 🛠️ Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
