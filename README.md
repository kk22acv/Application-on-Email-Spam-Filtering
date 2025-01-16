#Data Source
[Your Link Here](https://www.kaggle.com/datasets/marcelwiechmann/enron-spam-data?select=enron_spam_data.csv)


#Overview:

Phishing emails frequently imitate official messages, making it challenging to differentiate them from real communication. Conventional security measures, based on fixed rule systems, struggle to keep up with the advancing complexity of phishing strategies (Areej & Afrah, 2021). This challenge highlights the need for smart, flexible solutions. Introduce ML and NLP, technologies that can learn and adjust to new phishing patterns as time goes on. Machine Learning algorithms can undergo training on large datasets of both phishing and legitimate emails using supervised learning techniques (Benavides-Astudillo, et al., 2023).

1. **Text Preprocessing:**
   - Cleaning the text noises such as punctuation, numerals, stopwords etc using NLP.
2. **Feature Extraction:**
   - Extract features from email texts using TFIDF and Bag of Words.
3. **Data Preparation:**
   - Split data to prepare train and test sets.
   - Prepare data by Unigram & Bigram with TFIDF and Unigram & Bigram with Bag of Words 
4. **Model Preparation:**
   - Prepare model pipeline.
   - Tune the models to prepare optimized models using GridSearch with 5-fold cross validation.
   - Design the hybrid model.
5. **Spam Email Detection:**
   - Apply the models to the prepared data for spam email detection.
   - Obtain the prediction results.
   - Comapare the results and visualize the results.
## Requirements
The project requires Python 3.11 or above and the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `nltk`
- `sklearn`

Install dependencies using the following command:
```bash
pip install numpy pandas matplotlib seaborn nltk scikit-learn



```python

```





