# 📝 Sentiment Analysis: Research Paper Implementation

This project implements techniques from the research paper [**"Classification of Sentimental Reviews Using Machine Learning Techniques"**](https://www.sciencedirect.com/science/article/pii/S1877050915020529) on two different datasets:

1. 🎵 **Spotify App Reviews** – [Dataset](https://www.kaggle.com/datasets/alexandrakim2201/spotify-dataset/data)  
2. 🎬 **IMDB Movie Reviews** – [Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)

---

## 🔍 Methodology

The following NLP pipeline was used to perform sentiment classification:

1. **Exploratory Data Analysis (EDA)**  
   - Dataset structure, review length, class balance, and common keywords.

2. **Text Preprocessing**  
   - Lowercasing  
   - Removing punctuation, special characters, HTML tags, and URLs  
   - Removing stopwords  
   - **Stemming** using PorterStemmer  
   - Tokenization  

3. **Feature Extraction**  
   - **Count Vectorizer**  
   - **TF-IDF Vectorizer** (to balance word frequency and importance)

4. **Model Building**  
   - Applied **Naive Bayes** and **Support Vector Machine (SVM)** classifiers  
   - Supervised learning approach using labeled sentiment data

5. **Evaluation**  
   - Accuracy, Precision, Recall, F1-Score  
   - Confusion Matrix for error analysis

---

## 🏆 Results

| Dataset       | Accuracy | Notes                          |
|---------------|----------|--------------------------------|
| **Spotify**   | 88%      | 🥉 Bronze Medal on Kaggle with 1000+ views |
| **IMDB**      | 89%      | Complete implementation using same methodology |

---

## 📚 Resources

- 🔗 **Kaggle Notebook (Spotify)**: [Sentiment Analysis for Complete Beginners](https://www.kaggle.com/code/pragyatripathiii23/sentiment-analysis-for-complete-beginners/notebook)


