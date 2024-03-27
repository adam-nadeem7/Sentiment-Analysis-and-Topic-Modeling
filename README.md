# Final Project - E.On Case Study - Group 6

Welcome to the NPS Analysis Project repository. This project aims to enhance the understanding of customer loyalty and satisfaction through advanced Natural Language Processing (NLP) techniques. We've tackled several tasks, each contained in its separate notebook, to analyze customer feedback and Net Promoter Scores (NPS) for E.ON.

## Project Structure
- `Initial Exploration.ipynb`: Notebook containing initial exploration steps.
- `preprocessing.ipynb`: Notebook containing preprocessing steps including data exploration and processing.
- `bert.ipynb`: Notebook containing bert model for sentiment analysis.
- `all_sentiments.ipynb`: Notebook containing sentiment analysis (BERT + VADER and Textblob) to determine the polarity of customer feedback and its correlation with NPS scores.
- `NPS Correlation with Sentiment Score.ipynb`: Implements methodology for adjusting NPS scores based on the sentiment scores derived from textual feedback.
- `NPScorrelate_frequentwords.ipynb`: Implements methodology for adjusting NPS scores based on the frequent words approach. Implements it into sentiment score approach.
- `LDA.ipynb`: Focuses on identifying key themes and topics from customer comments using LDA.
- `BERT modeling.ipynb`: Focuses on identifying key themes and topics from customer comments using BERTopic.
- `Top2Vec.ipynb`: Focuses on identifying key themes and topics from customer comments using Top2Vec.
- `Topic modeling and Service Attributes.ipynb`: Identifies loyalty drivers and service attributes from customer feedback through noun extraction and feature engineering. Also implements NMF model to identify main and secondary drivers for NPS change.
