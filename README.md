# ChatGPT Review Analysis Using Python

## Project Overview
This project analyzes ChatGPT app reviews to understand user ratings, sentiment patterns, and recurring themes in customer feedback. Using Python and Natural Language Processing (NLP) techniques, the project transforms unstructured review text into meaningful insights that can support product improvement and decision-making.

## Objectives
- Clean and prepare review data for analysis.
- Explore rating distributions and review activity over time.
- Classify reviews into Positive, Neutral, and Negative sentiment.
- Identify frequently occurring phrases in each sentiment category.
- Categorize recurring negative phrases into broader issue themes.
- Develop actionable recommendations based on the findings.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- TextBlob
- NLTK
- Collections.Counter
- Jupyter Notebook / Google Colab

## Project Workflow
1. Data loading and structural inspection
2. Data cleaning and duplicate investigation
3. Exploratory Data Analysis (EDA)
4. Review date and review length analysis
5. Text preprocessing and stop-word removal
6. Sentiment polarity and subjectivity analysis
7. Sentiment classification and rating comparison
8. Combined two-word and three-word phrase-frequency analysis
9. Word-cloud visualizations
10. Negative issue identification and neutral theme analysis
11. Monthly sentiment trend analysis
12. Business recommendations and future scope

## Key Findings

### Overall Sentiment Distribution
- Positive: **73.16%**
- Neutral: **22.88%**
- Negative: **3.96%**

The results show that Positive was the dominant sentiment category according to TextBlob classification.

### Average Rating by Sentiment
- Positive: **4.67**
- Neutral: **4.29**
- Negative: **2.74**

The average ratings show a relationship between the assigned sentiment categories and users' star ratings.

### Sentiment Trends
- Highest negative sentiment: **August 2023 — 6.15%**
- Lowest negative sentiment: **July 2024 — 3.02%**
- Highest positive sentiment: **July 2024 — 74.73%**

Positive sentiment remained the largest category throughout the observed period.

### Negative Review Analysis
Recurring phrases included expressions such as "wrong answer", "wrong information", "doesnt work", and "please fix". These phrases were grouped into broader themes, including answer accuracy, app functionality, user experience, and troubleshooting.

## Recommendations
- Monitor negative sentiment, low-rated reviews, and recurring complaint phrases.
- Investigate accuracy-related complaints before drawing conclusions about system performance.
- Compare technical complaints with app crash logs, response times, login failures, app versions, and support tickets.
- Evaluate advanced sentiment-analysis models against a manually labelled review sample.

## Limitations
TextBlob is a lexicon-based sentiment-analysis tool and may misinterpret context, slang, negation, sarcasm, and ambiguous expressions. Some reviews may therefore receive a sentiment classification that does not match their apparent meaning. The results should be interpreted as analytical indicators rather than perfect classifications.

## Future Scope
- Evaluate machine-learning and transformer-based sentiment models.
- Measure model performance using accuracy, precision, recall, and F1-score.
- Apply topic modelling to discover recurring review themes.
- Integrate review data with technical and app-performance metrics.

## Project Files
- `01_chatgpt_reviews_csv` — the dataset used for the analysis
- `02_ChatGPT_Reviews_Analysis.ipynb` — notebook containing the analysis, code, and visualizations.
  

## Conclusion
This project demonstrates how Python, data analysis, visualization, and NLP techniques can be used to analyze a large volume of customer reviews and derive insights that may support product and customer-experience improvements.
