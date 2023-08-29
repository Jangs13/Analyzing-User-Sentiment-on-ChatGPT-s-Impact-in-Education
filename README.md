# Analyzing-User-Sentiment-on-ChatGPT-s-Impact-in-Education

**Overview:**  

This project aims to understand the sentiment of Twitter users regarding the impact of ChatGPT in the field of education. By analyzing tweets collected between 2021 and 2022, the study evaluates user opinions to gauge the potential influence of ChatGPT in educational settings.

**Importance:**  

Sentiment analysis is a crucial tool for assessing the efficacy of software and products. This study focuses on analyzing user sentiment towards ChatGPT in education, drawing parallels with past instances like the controversial shutdown of Tay AI within 16 hours due to user perception of corruption. The insights from user sentiments can guide software improvement and updates.

**Research Questions:**  

* How are Twitter users responding to ChatGPT's impact in the field of education?
* How can a comprehensive dataset be constructed for conducting this experiment?
  
**Contributions:**  

The project contributes by creating an exclusive dataset that provides deeper insights into the sentiments surrounding ChatGPT and its role in education. This dataset can serve as a foundation for future studies on the same topic. The findings of this study can be compared with the impact of other AI bots, such as BARD, in the education sector.

**Methodology:**  

The project involved exploratory data analysis (EDA) of approximately 100,000 tweets related to education and ChatGPT. Tweets were scraped using Snscrape to create the dataset. The dataset creation process was challenging, involving multiple iterations to ensure data quality.

Sentiment analysis was performed using the VADER (Valence Aware Dictionary and Sentiment Reasoner) tool. VADER is designed for sentiment analysis in social media texts and takes into account challenges like non-standard language and sarcasm. SentimentIntensityAnalyzer from the NLTK library was used to calculate sentiment scores.

The project employed supervised learning by training a Logistic Regression model on the sentiment scores obtained from VADER. An 80-20 split was used for training and testing the model. The sentiment scores were converted into binary labels, and TF-IDF Vectorization was applied to build a sparse matrix and remove stop words.

SentiWordNet, a lexical resource for sentiment analysis, was also utilized. It assigns sentiment scores to synsets in WordNet, allowing determination of overall sentiment polarity by aggregating synset scores.

**Technologies Used:**

Snscrape for data scraping

VADER for sentiment analysis

NLTK for text processing

Logistic Regression for Supervised Learning

TF-IDF Vectorization for feature engineering

SentiWordNet for synset-based sentiment analysis

**Outcome:**
The project sheds light on user sentiments towards ChatGPT's impact in education through the lens of Twitter data. By utilizing advanced sentiment analysis techniques and methodologies, this study provides a deeper understanding of how AI technologies are perceived in educational contexts.



