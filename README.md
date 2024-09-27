# **Text Mining Analysis on Cyberbullying Tweets**

![Stop Cyberbullying](https://www.naquera.es/sites/www.naquera.es/files/img/noticias/foto_714.jpg)

## **Project Overview**

In this project, we work with a dataset of tweets labeled as either containing **hate speech** or not. 

One of the most pressing issues on the internet today is the prevalence of negative attitudes toward various groups based on **ethnicity**, **gender**, **religion**, or **political ideology**. This study focuses on identifying and analyzing the presence of **hate speech** in tweets. The dataset used for this analysis contains manually labeled tweets sourced from the Kaggle platform.

[**Kaggle Dataset**](https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification/data)

Originally, each tweet in the dataset was assigned to one of the following categories:
- **Religion**
- **Age**
- **Ethnicity**
- **Gender**
- **Other Cyberbullying**
- **Not Cyberbullying**

For the purpose of this analysis, the labels have been simplified into **binary categories** (1 or 0), indicating whether the tweet contains hate speech.

---

## **Objective**

The main objective of this study is to develop and train **classification models** capable of accurately categorizing tweets as either **containing hate speech** or not. 

To achieve this, various stages of **data exploration**, **preprocessing**, and **text vectorization** will be applied. The study will also involve the training and evaluation of multiple **machine learning models**.

---

## **Approach**

### 1. Exploratory Data Analysis (EDA)

The initial phase involves an **exploratory analysis** of the dataset. This includes:
- Assessing the number of documents (tweets),
- Visualizing the distribution of tweet lengths,
- Generating word clouds, and
- Conducting additional exploratory analyses to gain insights into the data.

This step is crucial for understanding the structure and content of the data. We will also include text **normalization techniques** to clean and preprocess the data. These techniques include:
- Removing stop words,
- Eliminating punctuation, and
- Lemmatization or stemming to reduce words to their base form.

---

### 2. Text Vectorization

To convert the tweets into a machine-readable format, various text vectorization strategies will be applied. These include:
- **TF-IDF (Term Frequency-Inverse Document Frequency)** to capture the importance of words relative to the entire corpus,
- **Word Embeddings** for capturing semantic relationships between words.

Additional features, such as **sentiment analysis** or **lexical features**, may be incorporated to enhance the model’s ability to detect hate speech.

---

### 3. Model Training and Validation

The final phase involves training and evaluating multiple **classification models** to identify the best-performing algorithm. 

At least three different **machine learning classifiers** will be tested. After evaluating their general performance, **hyperparameter tuning** will be performed to optimize the best model. The following metrics will be used for evaluation:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **ROC-AUC**

The goal is to select the most suitable model that can accurately detect hate speech in tweets, providing valuable insights into the nature of **cyberbullying** on social media platforms.

---

