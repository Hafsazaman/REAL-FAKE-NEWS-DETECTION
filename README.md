# Real vs Fake News Detection using Machine Learning

## 📌 Objective
The objective of this project is to build a machine learning model that can classify news articles as **Real or Fake** using Natural Language Processing (NLP) techniques.

---

## 📊 Dataset Information
The dataset contains labeled news articles with the following columns:

- Title / News Text  
- Subject  
- Date (if available)  
- Label (Real or Fake)

The dataset is used to train a classification model for detecting misinformation.

---

## 🧠 What I Did in This Project

- Loaded and explored the dataset  
- Performed data cleaning and preprocessing  
- Removed stopwords, punctuation, and special characters  
- Converted text data into numerical format using TF-IDF Vectorizer  
- Split data into training and testing sets  
- Trained a classification model  
- Predicted whether news is real or fake  
- Evaluated model performance  

---

## 🛠️ Tools & Libraries Used

- Google Colab  
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK (for text preprocessing)  
- Matplotlib (for visualization)

---

## 🤖 Machine Learning Model

- Model Used:LogisticRegression(max_iter=1000),
    "Decision Tree": DecisionTreeClassifier(),
    "Random Forest": RandomForestClassifier(),
    "Naive Bayes": MultinomialNB(),
    "KNN": KNeighborsClassifier(n_neighbors=5),
    "ANN (MLP) Logistic Regression / Naive Bayes  
- Type: Supervised Learning (Classification)  
- Goal: Classify news as Real or Fake  

---

## 🔤 NLP Techniques Used

- Text Cleaning  
- Stopword Removal  
- Tokenization  
- TF-IDF Vectorization  

---

## 📊 Model Evaluation

The model was evaluated using:

- Accuracy Score  
- Confusion Matrix  
- Precision & Recall  

These metrics help measure how well the model detects fake news.

---

## 📈 Key Insights

- Text preprocessing improves model accuracy  
- Fake news detection is a classification problem  
- TF-IDF helps convert text into meaningful features  
- Simple ML models can perform well on text classification  

---

## 🚀 How to Run the Project

1. Open Google Colab  
2. Upload dataset or load from Drive  
3. Install required libraries:

```python
!pip install pandas numpy scikit-learn nltk

📁 Output
Cleaned dataset
Trained classification model
Predictions (Real / Fake News)
Accuracy and evaluation metrics
👩‍💻 Author

Name: HAFSA ZAMAN
