# Medical Text Classification

This project explores **medical text classification** using different text representation techniques combined with classical machine learning algorithms.  
The goal is to compare the performance of multiple embedding methods on a medical dataset to evaluate which approach yields the best classification results.

---

## 📂 Project Structure
- `Dataset review.ipynb` – Jupyter notebook with dataset exploration, preprocessing, and experiments.  
- `BSP3 Final.pdf` – Final project report.  
- `BSP3 French Abstract.pdf` – Abstract in French.  
- `.gitignore` – Git ignore rules.  

---

## 🧾 Methodology

### Text Representations
- **TF-IDF**  
- **Word2Vec**  
- **GloVe**  
- **Sentence-BERT (SBERT)**  
- **BioBERT**  

### Classifiers
- **Naïve Bayes**  
- **Support Vector Machine (SVM)**  
- **Decision Tree**  
- **Logistic Regression**  

Each combination of embedding technique and classifier was trained and evaluated on the medical classification dataset.

---

## ⚙️ Steps Performed
1. Data preprocessing (cleaning, tokenization, normalization).  
2. Feature extraction using TF-IDF, Word2Vec, GloVe, SBERT, and BioBERT.  
3. Model training with Naïve Bayes, SVM, Decision Tree, and Logistic Regression.  
4. Performance evaluation and comparison (accuracy, F1-score, precision, recall).  
5. Analysis of results to identify the most effective embeddings and models.  

---

## 📊 Results
- Classical methods like **TF-IDF + SVM** showed strong baselines.  
- Contextual embeddings like **SBERT** and **BioBERT** significantly improved performance in capturing semantic meaning.  
- Logistic Regression and SVM consistently outperformed Decision Trees and Naïve Bayes with modern embeddings.  

(Detailed numerical results are available in the notebook and report.)

