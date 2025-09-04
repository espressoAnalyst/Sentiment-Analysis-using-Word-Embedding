#  📊  Sentiment-Analysis-using-Word-Embedding

## 🌟 Overview
This project analyzes customer reviews to identify sentiment trends using **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques.  
The goal is to categorize sentiments as **positive**, **neutral**, or **negative** and provide actionable insights for businesses. 💡

---

## 🛠 Features
- 🧹 **Text Preprocessing:** Clean raw review data  
- 📝 **Vectorization Techniques:**  
  - Bag of Words (BoW)  
  - Word2Vec (CBOW & Skip-gram)  
  - GloVe embeddings  
- 🤖 **ML Models:**  
  - Random Forest 🌲  
  - Gradient Boosting 🚀  
  - AdaBoost ⚡  
  - Naive Bayes 🧠  
- 📊 **Model Evaluation:** Macro F1-score, classification report, confusion matrix  
- 🎨 **Visualization:** Confusion matrices for model performance  

---

## 📂 Dataset
Customer reviews with labeled sentiments: **Positive 👍, Neutral 😐, Negative 👎**  

---

## 🔍 Methodology
1. **Data Preprocessing** 🧹  
   - Clean and normalize text  
   - Remove stopwords, punctuation & irrelevant characters  

2. **Text Vectorization** 📝  
   - Convert text into numerical representations using BoW, Word2Vec, and GloVe embeddings  

3. **Model Training** 🤖  
   - Train/test split (80/20)  
   - Train multiple classifiers (Random Forest, Gradient Boosting, AdaBoost, Naive Bayes)  
   - Evaluate using **Macro F1-score**  

4. **Model Evaluation** 📊  
   - Select best-performing model  
   - Visualize results using **Confusion Matrix**  

---

- Future improvement: Hyperparameter tuning & experimenting with advanced models for better performance 🎯  

---

## 💼 Business Applications
- Identify customer concerns and take proactive actions ⚡  
- Tailor marketing strategies based on sentiment 📢  
- Highlight positive feedback in promotions 🌟  
- Make informed inventory & operational decisions 📦  

---

## 🔮 Future Work
- Hyperparameter tuning for improved performance ⚙️  
- Experiment with deep learning models (LSTM, Transformers) 🧠  
- Support multilingual reviews 🌍  

---

## 📦 Requirements
- Python 3 
- Libraries: `pandas`, `scikit-learn`, `gensim`, `matplotlib`, `seaborn`  

---

## 💻 Usage
1. Clone the repository:  
```bash
git clone <repo-url>
