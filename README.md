# NLP-Sentiment-Analysis

![WhatsApp Image 2024-10-02 at 11 04 06_95d6d4bd](https://github.com/user-attachments/assets/875309f3-9a88-4a86-a3c8-e989647a65a9)

## Team Members
- Royce Bett
- Catherine Wangui
- Wilson Mutungu
- Paulette Ndeda

## Contents
- Business overview
- Data Understanding
- Data Preparation
- Exploratory Data Analysis
- Modeling and Evaluation
- Summary
- Conclusions
- Recommendations

## Business Overview
### Introduction
We have arrived at a point in time where, a large percentage of the population has access to the internet. Through that, there are many social media platforms where people can share their opinions on various things, making them an invaluable resource for companies looking to harness this to optimise business practices.

### Business Understanding
As stated above, Twitter is an invaluable resource for companies for gathering data on public sentiment. Apple and Google are two such companies that stand to benefit from this. They are constantly and consistently designing and rolling out new products and services, and public feedback is crucial to the optimization of products and rollout.

### Business Problem
The foremost issue we need to address the need for a system to more clearly and accurately group the data in away that can inform future company decisions. A natural language processing model is needed to classify tweets by whether they are positive, negative or neutral.

### Metrics of Success
- *Accuracy.*:  Measure the frequency with which the sentiment classification model correctly separates tweets into positive, negative, or neutral sentiments.

- *Precision, Recall, and F1 Score*: These metrics measure the model's ability to balance precision(correctly classification) and recall (identifying all positive/negative sentiments).

### Data Understanding
The data was acquired from this site. Contributors evaluated tweets about multiple brands and products. The crowd was asked if the tweet expressed positive, negative, or no emotion towards a brand and/or product. If some emotion was expressed they were also asked to say which brand or product was the target of that emotion.

### Data Preparation
 - Checking for duplicates
 - Data Cleaning
 - Dealing with missing values

### EDA
 - Sentiment distribution

![download](https://github.com/user-attachments/assets/cc8f74a2-8266-4661-a515-ced39e221172)

 - Tweet length distribution

![download](https://github.com/user-attachments/assets/234ec6e0-b0da-40ff-a604-37a0fb73fa78)

 - Common words across tweets

![download](https://github.com/user-attachments/assets/2ba9b72c-464c-4ab1-815e-6da77b9ab434)

 - Wordcloud for sentiment categories

![download](https://github.com/user-attachments/assets/5de7b14a-5032-46e6-a1d2-e617c0faaaac)
![download](https://github.com/user-attachments/assets/2e8b1f30-ff35-4a60-a8e4-039762d8efae)
![download](https://github.com/user-attachments/assets/0d452974-c602-4aa0-af7e-4da79202e1f3)

 - Sentiment distribution by product

![download](https://github.com/user-attachments/assets/54683b34-4a60-4f78-a1cd-d1c9a96bb65f)


### Modelling and Evaluation
We chose to use a few models, which included:
 - Logistic Regression.

![download](https://github.com/user-attachments/assets/d5de0e9d-a674-4035-bd15-ed18811710e9)

 - Multinomial Naive Bayes

![download](https://github.com/user-attachments/assets/ea039dd9-9e0a-4c3f-9816-181fabd317f8)

 - Random Forest
![download](https://github.com/user-attachments/assets/157af909-9bef-46aa-a309-f8c52e0aa4c4)

