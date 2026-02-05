# 📊 Task-04: Sentiment Analysis – Twitter Entity Dataset

## 📌 Internship
**Prodigy Infotech – Data Science Internship**

## 📌 Task Objective
The objective of this task is to **analyze and visualize sentiment patterns in social media data** to understand public opinion and attitudes toward **specific topics or brands**.

This task focuses on applying **Natural Language Processing (NLP)** and **machine learning techniques** to classify text data into sentiment categories and extract meaningful insights from real-world social media content.

## 📂 Dataset Information

- **Dataset Name:** Twitter Entity Sentiment Analysis  
- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis  
- **Records:** Large-scale Twitter dataset  
- **Features:**
  - Tweet ID  
  - Topic / Entity  
  - Tweet Text  
  - Sentiment Label  

- **Sentiment Classes:**
  - Positive
  - Negative
  - Neutral
  - Irrelevant

The dataset contains tweets related to various entities, enabling analysis of public opinion across different topics.

## 🛠️ Technologies & Libraries Used

- **Python**
- **Jupyter Notebook**
- **Pandas & NumPy** – Data manipulation
- **NLTK** – Text preprocessing
- **Scikit-learn** – Feature extraction & model building
- **Matplotlib & Seaborn** – Data visualization
- **WordCloud** – Text visualization

## 🔍 Steps Performed

### 1️⃣ Data Loading
- Loaded the Twitter sentiment dataset using Pandas.
- Inspected dataset structure, size, and column details.

### 2️⃣ Data Exploration & Cleaning
- Analyzed sentiment class distribution.
- Cleaned tweet text by:
  - Removing URLs, mentions, and special characters
  - Converting text to lowercase
  - Removing stopwords

### 3️⃣ Text Preprocessing
- Tokenized and cleaned tweet content.
- Prepared text data for feature extraction.

### 4️⃣ Feature Extraction
- Converted textual data into numerical form using **TF-IDF Vectorization**.
- Captured important word patterns and frequencies.

### 5️⃣ Train-Test Split
- Split the dataset into training and testing sets (80/20 ratio).

### 6️⃣ Model Building
- Implemented **Logistic Regression** for multi-class sentiment classification.
- Trained the model on TF-IDF features.

### 7️⃣ Model Evaluation
- Evaluated model performance using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

### 8️⃣ Visualization
- Visualized sentiment distribution using bar plots.
- Generated **word clouds** for each sentiment category.
- Displayed confusion matrix as a heatmap.


## 📈 Results & Insights

- The model successfully classified tweets into sentiment categories.
- Visualizations revealed public opinion trends across different topics.
- Word clouds highlighted frequently used words associated with each sentiment.
- The project demonstrated how NLP can be used to analyze large-scale social media data effectively.


## 📌 Key Learnings

- Practical implementation of **Natural Language Processing (NLP)** techniques.
- Importance of text cleaning and preprocessing in sentiment analysis.
- Understanding TF-IDF feature extraction for text data.
- Experience in building and evaluating machine learning classification models.
- Gained insights into public sentiment analysis using social media data.


## 🚀 Conclusion

This task provided hands-on experience in **sentiment analysis and text-based machine learning workflows**.  
It enhanced understanding of how data science and NLP techniques can be applied to analyze public opinion and support **data-driven decision-making** in marketing and brand analysis.


## 📌 Acknowledgment
Thanks to **Prodigy Infotech** for providing the opportunity to work on real-world data science and machine learning tasks.
