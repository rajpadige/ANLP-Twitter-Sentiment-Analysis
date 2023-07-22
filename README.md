# Twitter Sentiment Analysis on ChatGPT using Tweepy and Natural Language Processing
## Project Overview
This project was conducted between January 2023 and May 2023 to analyze the sentiment of Twitter users towards ChatGPT, a language model based on the GPT-3.5 architecture. The goal was to gain insights into public opinions and reactions related to ChatGPT. The analysis involved collecting live Twitter data, preprocessing it to remove noise and irrelevant information, and implementing sentiment analysis using the VADER model. Additionally, topic modeling was performed to identify key themes associated with ChatGPT.

## Methodology
### Data Collection
Around 5,000 tweets related to ChatGPT were collected using the Twitter API with the help of Tweepy. The tweets were obtained in real-time to ensure the data was up-to-date and relevant to the analysis.

### Data Preprocessing
The collected tweets underwent extensive preprocessing to clean the data for further analysis. The preprocessing steps included:

### Removal of stop words: Common words that do not contribute significantly to the meaning of the text were removed to reduce noise.
### Special character removal: Non-alphanumeric characters and symbols were removed to retain only the text.
### URL removal: URLs and hyperlinks were eliminated as they do not add value to sentiment analysis.
### Lemmatization: Words were converted to their base or root form to standardize variations of the same word.

## Sentiment Analysis
The VADER (Valence Aware Dictionary for Sentiment Reasoning) model was used for sentiment analysis. This model is specifically designed for social media text and can categorize tweets into positive, neutral, and negative sentiments based on lexicon and rule-based methods.

## Data Exploration
Word count distribution was explored after the data preprocessing stage. The analysis revealed that the majority of tweets contained 250 words or fewer, indicating that users tended to express their opinions concisely.

## Topic Modeling
Topic modeling was conducted to identify key themes present in the tweets related to ChatGPT. Through this analysis, the following themes were discovered:

* AI Effect
* Engineering
* Questions
* Language
* Cybersecurity
* Intelligence
* Future Technology
* Amazon
* Shopping
* Sentiment Results
The overall sentiment towards ChatGPT on Twitter was found to be positive. Users generally expressed positive opinions and experiences related to the language model. However, it was observed that the least positive tweets were associated with Cybersecurity, suggesting potential concerns or negative feedback in this area.

## Conclusion
The Twitter Sentiment Analysis on the ChatGPT project provided valuable insights into the public's perception of the language model. Overall, ChatGPT was well-received, with positive sentiment dominating the Twitter discourse. The identified themes shed light on the areas where ChatGPT is commonly discussed, ranging from AI and Engineering to Shopping and Future Technology.

Understanding public sentiment towards AI models like ChatGPT is crucial for developers and stakeholders to gauge its acceptance and address any concerns raised by users. The combination of Tweepy, Natural Language Processing, and the VADER model proved to be effective in analyzing Twitter data at scale and deriving meaningful insights from it.

The results of this analysis can be utilized to improve and optimize ChatGPT further, making it a more effective and user-friendly tool for language processing tasks. It is important to note that sentiment analysis on social media data is dynamic, and continuous monitoring and analysis are essential to keep up with the ever-changing sentiments and opinions of users.
