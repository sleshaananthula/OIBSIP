<h1 align="center" style="font-size:38px;">Task 4: Email Spam Detection with Machine Learning
</h1>
<h2 style="font-size: 28px;"> Objective</h2>

Build a machine learning model that can classify emails/SMS messages as **Spam** or **Not Spam (Ham)**.

<h2 style="font-size: 28px;"> Description</h2>

Spam emails often contain scams, cryptic messages, or phishing content. This project uses **Natural Language Processing (NLP)** techniques to process text data and train a classifier that can automatically detect spam messages.

<h2 style="font-size: 28px;"> Tools & Libraries</h2>

- Python
- Pandas, NumPy
- NLTK / re (for text preprocessing)
- Scikit-learn (CountVectorizer / TF-IDF, classification models)
- Matplotlib, Seaborn

<h2 style="font-size: 28px;"> Approach</h2>

1. **Data Loading & Cleaning** – Load the dataset and remove duplicates/null values.
2. **Text Preprocessing**
   - Lowercasing, removing punctuation and stopwords
   - Tokenization and stemming/lemmatization
3. **Feature Extraction** – Convert text into numerical vectors using **CountVectorizer** or **TF-IDF**.
4. **Model Building** – Train classification models such as:
   - Multinomial Naive Bayes
   - Logistic Regression
   - Support Vector Machine (SVM)
5. **Model Evaluation** – Evaluate using accuracy, precision, recall, F1-score, and confusion matrix.
6. **Conclusion** – Identify the best model for spam detection.

<h2 style="font-size: 28px;"> Dataset</h2>

- Source: Link provided in the OIBSIP task list (SMS Spam Collection dataset, Kaggle/UCI).

<h2 style="font-size: 28px;">Results</h2>

- Best model: `<model name>` with accuracy of **XX%**
- Add confusion matrix screenshot here.

<h2 style="font-size: 28px;">How to Run</h2>

```bash
pip install -r requirements.txt
jupyter notebook spam_detection.ipynb
```
