# PRODIGY_DS_04

# 📊 Sentiment Analysis and Visualization of Social Media Data

## 📌 Project Overview

This project was completed as part of the **Data Science Virtual Internship** at **Prodigy InfoTech**.

The objective of this project is to analyze sentiment patterns in Twitter data and visualize public opinion toward different brands and topics. By applying data cleaning, exploratory data analysis (EDA), and basic Natural Language Processing (NLP) techniques, the project uncovers how users express **Positive**, **Negative**, **Neutral**, and **Irrelevant** sentiments across various discussions.

---

## 🎯 Objective

Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes toward different brands and topics.

---

## 📂 Dataset

**Dataset:** `twitter_training.csv`

The dataset contains Twitter posts along with their corresponding sentiment labels and discussion topics.

### Dataset Features

| Feature | Description |
|---------|-------------|
| **ID** | Unique identifier for each tweet |
| **Topic** | Brand or topic discussed in the tweet |
| **Sentiment** | Positive, Negative, Neutral, or Irrelevant |
| **Tweet** | Original tweet text |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Regular Expressions (`re`)
- WordCloud
- Collections (`Counter`)

---

## 📋 Project Workflow

### 1️⃣ Data Loading

- Imported the Twitter sentiment dataset using Pandas.

### 2️⃣ Data Understanding

- Explored dataset dimensions.
- Examined column names.
- Checked data types.
- Identified unique topics and sentiment categories.

### 3️⃣ Data Cleaning

- Renamed dataset columns.
- Removed missing tweet values.
- Removed duplicate records.
- Prepared the dataset for analysis.

### 4️⃣ Exploratory Data Analysis (EDA)

Performed various analyses including:

- Sentiment Distribution
- Sentiment Percentage Pie Chart
- Top 10 Most Discussed Topics
- Topic-wise Sentiment Distribution
- Sentiment Heatmap

### 5️⃣ Text Preprocessing

Cleaned tweet text by:

- Converting text to lowercase
- Removing URLs
- Removing mentions
- Removing numbers
- Removing punctuation
- Removing extra spaces

### 6️⃣ Text Analysis

- Generated cleaned tweet text.
- Calculated the most frequent words.
- Created Word Clouds.
- Identified the Top 20 Frequent Words.

### 7️⃣ Additional Analysis

- Tweet Length Distribution by Sentiment
- Top 10 Positive Topics
- Top 10 Negative Topics

---

## 📊 Visualizations Included

- Sentiment Distribution Bar Chart
- Sentiment Percentage Pie Chart
- Top 10 Most Discussed Topics
- Topic-wise Sentiment Count Plot
- Sentiment Heatmap
- Top 20 Frequent Words
- Positive Word Cloud
- Negative Word Cloud
- Tweet Length Box Plot
- Top Positive Topics
- Top Negative Topics

---

## 📈 Key Insights

- Positive and Negative sentiments dominate the dataset.
- Public opinion varies significantly across different brands and topics.
- Some topics receive substantially higher user engagement than others.
- Frequently occurring words reveal common discussion themes.
- Tweet length differs across sentiment categories.
- Sentiment analysis provides valuable insights into customer opinions and brand perception.

---

## 💼 Business Applications

This analysis can support organizations in:

- Brand Reputation Monitoring
- Customer Feedback Analysis
- Product Improvement
- Marketing Campaign Evaluation
- Customer Experience Enhancement
- Competitor Analysis
- Social Media Monitoring

---

## 🚀 Future Scope

This project can be further enhanced by:

- Building Machine Learning models for sentiment classification.
- Applying TF-IDF and Count Vectorization techniques.
- Using advanced NLP preprocessing methods.
- Implementing Deep Learning models such as LSTM or BERT.
- Performing real-time Twitter sentiment analysis using APIs.

---

## 📁 Project Structure

```text
PRODIGY_DS_04/
│
├── PRODIGY_DS_04_Sentiment_Analysis.ipynb
├── twitter_training.csv
├── README.md
├── requirements.txt
└── screenshots/
```

---

## ▶️ How to Run

### 1. Clone this repository

```bash
git clone https://github.com/your-username/PRODIGY_DS_04.git
```

### 2. Navigate to the project folder

```bash
cd PRODIGY_DS_04
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **`PRODIGY_DS_04_Sentiment_Analysis.ipynb`** and run all cells sequentially.

---

## 📦 Requirements

The project requires the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- wordcloud

Install them using:

```bash
pip install -r requirements.txt
```

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Text Preprocessing
- Word Frequency Analysis
- Word Cloud Generation
- Basic Natural Language Processing (NLP)
- Sentiment Analysis
- Business Insight Generation
- Working with Real-world Social Media Data

---

## 👨‍💻 Author

**Shubham Kumavat**

Data Science Virtual Intern

**Prodigy InfoTech**

---

## 🙏 Acknowledgement

This project was completed as part of the **Data Science Virtual Internship** offered by **Prodigy InfoTech**.

The Twitter sentiment dataset was used for educational purposes to demonstrate sentiment analysis, text preprocessing, and data visualization techniques.

---

## ⭐ Support

If you found this project useful, consider giving this repository a ⭐ on GitHub.

Feel free to fork this repository, open an issue, or suggest improvements.
