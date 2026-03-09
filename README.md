# Mental Health Classifier

An NLP deep learning project that analyzes text to classify whether 
there are early indicators of depression or not.

# Objective
Build and compare multiple NLP models to detect early signs of 
depression from text data — helping enable earlier mental health intervention.

# Problem Statement
Given a text input (e.g. social media posts, written statements), 
the model predicts:
- 1 → Possible early depression indicators detected
- 0 → No indicators detected

# 1. Data Exploration
- Class distribution analysis (bar chart + pie chart)
- Word frequency analysis
- Dataset statistics (total words, unique words)

# 2. Data Preprocessing
- Handling missing values
- Stop word removal
- Lemmatization
- Tokenization
- Handling imbalanced data using **Random Oversampling**

# 3. Visualization
- Word Cloud (full dataset)
- Word Cloud (positive class vs negative class)

# 4. Vectorization
- TF-IDF Vectorizer (for Naive Bayes)
- Keras TextVectorization (for deep learning models)


# 5. Models Built & Compared (model, type)
1- Naive Bayes (MultinomialNB) , Classical ML 
2- LSTM , Deep Learning 
3- GRU , Deep Learning 


 # 6. Evaluation Metrics
- Accuracy, Precision, Recall
- Confusion Matrix
- ROC Curve & AUC Score
- Classification Report

# Tools & Libraries
- Python
- Pandas, NumPy
- NLTK
- Scikit-learn
- TensorFlow / Keras
- Imbalanced-learn
- Matplotlib, Seaborn
- WordCloud
- Google Colab

Built with 💙 to support early mental health awareness
