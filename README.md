📌 Project Overview
This project was completed as part of the Data Science Virtual Internship at Prodigy InfoTech.

The objective of this project is to analyze sentiment patterns in Twitter data and visualize public opinion toward different brands and topics. Using Python-based data analysis and visualization techniques, the project explores how users express positive, negative, neutral, and irrelevant sentiments across various discussions.

🎯 Objective
Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards different topics or brands.

📂 Dataset
Dataset: twitter_training.csv

The dataset contains Twitter posts labeled with their corresponding sentiment and topic.

Features
ID: Unique identifier

Topic: Brand or topic being discussed

Sentiment: Positive, Negative, Neutral, or Irrelevant

Tweet: Original tweet text

🛠️ Technologies Used
Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Regular Expressions (re)

WordCloud

Collections (Counter)

📋 Project Workflow
1. Data Loading
Imported the Twitter dataset using Pandas.

2. Data Understanding
Examined dataset structure.

Checked column names.

Inspected data types.

Explored unique topics and sentiments.

3. Data Cleaning
Renamed columns.

Removed missing tweet values.

Removed duplicate records.

4. Exploratory Data Analysis (EDA)
Performed several visual analyses including:

Sentiment Distribution

Sentiment Percentage Pie Chart

Top 10 Most Discussed Topics

Topic-wise Sentiment Distribution

Sentiment Heatmap

5. Text Preprocessing
Cleaned tweet text by:

Converting text to lowercase

Removing URLs

Removing mentions

Removing numbers

Removing punctuation

Removing extra spaces

6. Text Analysis
Created cleaned tweet text.

Calculated most frequent words.

Generated Word Clouds.

Identified Top 20 Frequent Words.

7. Additional Analysis
Tweet Length Distribution by Sentiment

Top 10 Positive Topics

Top 10 Negative Topics

📊 Visualizations Included
Bar Chart of Sentiment Distribution

Pie Chart of Sentiment Percentage

Top 10 Discussed Topics

Topic-wise Sentiment Count Plot

Sentiment Heatmap

Top 20 Frequent Words

Positive Word Cloud

Negative Word Cloud

Tweet Length Box Plot

Top Positive Topics

Top Negative Topics

📈 Key Insights
Positive and Negative sentiments dominate the dataset.

Different brands receive varying public opinions.

Certain topics attract significantly higher user engagement.

Frequently occurring words reveal the main discussion themes.

Tweet length varies across different sentiment categories.

Sentiment analysis provides valuable insights into customer opinions and public perception.

💼 Business Applications
This analysis can help organizations in:

Brand Reputation Monitoring

Customer Feedback Analysis

Product Improvement

Marketing Campaign Evaluation

Customer Experience Enhancement

Competitor Analysis

Social Media Monitoring

🚀 Future Scope
This project can be extended by:

Building Machine Learning models for automatic sentiment prediction.

Applying TF-IDF and Count Vectorization.

Using advanced NLP techniques.

Implementing Deep Learning models such as LSTM or BERT.

Performing real-time Twitter sentiment analysis using APIs.

📁 Project Structure
Plaintext
PRODIGY_DS_04/
│
├── PRODIGY_DS_04_Sentiment_Analysis.ipynb
├── twitter_training.csv
├── README.md
├── requirements.txt
└── screenshots/
▶️ How to Run
Clone this repository:

Bash
git clone <repository-url>
cd PRODIGY_DS_04
Install the required libraries:

Bash
pip install -r requirements.txt
Open the notebook in Jupyter Notebook or JupyterLab:

Bash
jupyter notebook PRODIGY_DS_04_Sentiment_Analysis.ipynb
Run all cells sequentially.

📚 Learning Outcomes
Through this project, I gained practical experience in:

Data Cleaning

Exploratory Data Analysis (EDA)

Data Visualization

Text Preprocessing

Basic Natural Language Processing (NLP)

Sentiment Analysis

Business Insight Generation

Working with Real-world Social Media Data

👨‍💻 Author
Shubham Kumavat

Data Science Virtual Intern

Prodigy InfoTech

🙏 Acknowledgement
This project was completed as part of the Data Science Virtual Internship offered by Prodigy InfoTech.

⭐ If you found this project useful, consider giving the repository a star!
