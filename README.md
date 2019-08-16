# AV-Sentiment-Analysis-Hackathon

## Problem Statement

### Sentiment Analysis for drugs/medicines
Nowadays the narrative of a brand is not only built and controlled by the company that owns the brand. For this reason, companies are constantly looking out across Blogs, Forums, and other social media platforms, etc for checking the sentiment for their various products and also competitor products to learn how their brand resonates in the market. This kind of analysis helps them as part of their post-launch market research. This is relevant for a lot of industries including pharma and their drugs.
 

**The challenge is that the language used in this type of content is not strictly grammatically correct. Some use sarcasm. Others cover several topics with different sentiments in one post. Other users post comments and reply and thereby indicating his/her sentiment around the topic.**

Sentiment can be clubbed into 3 major buckets - **Positive, Negative and Neutral Sentiments.**


You are provided with data containing samples of text. This text can contain one or more drug mentions. Each row contains a unique combination of the text and the drug mention. Note that the same text can also have different sentiment for a different drug.

Given the text and drug name, the task is to predict the sentiment for texts contained in the test dataset.

### Data Description
**train.csv**
Contains the labelled texts with sentiment values for a given drug
 
|Variable|	Definition|
|----|----|
|unique_hash |Unique ID|
|text|text pertaining to the drugs|
|drug |drug name for which the sentiment is provided|
|sentiment	|(Target) 0-positive, 1-negative, 2-neutral  |


**test.csv**
test.csv contains texts with drug names for which the participants are expected to predict the correct sentiment
 

### Evaluation Metric
The metric used for evaluating the performance of the classification model would be macro F1-Score.
