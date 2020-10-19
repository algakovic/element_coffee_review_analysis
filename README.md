# Element coffee Review Analysis

#### Semantic analysis of reviews and Word Cloud Imageing for Element Coffee
![Header Image](https://scontent-iad3-1.cdninstagram.com/v/t51.29350-15/106366391_713884452737352_277651400985110000_n.jpg?_nc_cat=107&_nc_sid=8ae9d6&_nc_ohc=GUoNXHiB7Y4AX8hmlZG&_nc_ht=scontent-iad3-1.cdninstagram.com&oh=a0bbb0ac5cc6ac5fa14447df046d7b60&oe=5FB1DEBC)
Element Coffee Late Art, [Image Source:](https://www.elementcoffee.co.uk "www.elementcoffee.co.uk")
## Executive Summary:¶
Element Coffee requested an analysis on the reviews for their brick and mortar coffee shop in Northfields London. Data was Extracted using Google Cloud and the Google My Business API. Nlp was used to classify the sentiment of reviews as either Negative or Positive. with most (91.4%) reviews scoring a 5 Star Rating. A Word Cloud of the reviews was created to display the most important words and concepts that occur in the reviews.

## Contents:
1. **Importing modules and libraries**  
2. **Accessing Data with google Auth 2.0 Playground**  
3. **Save and Import Data to and from .csv file**  
4. **Data Cleaning**  
5. **Exploratory Data Analysis 1**
6. **NLP Sentiment-Analysis with Transformers Library**  
    6.1 Pre-Processing for NLP  
7. **Exploratory Data Analysis 2**  
8. **WordCloud Image Generation**  
    8.1 WordCloud for All Reviews  
    
## Methodology
- Primary ETL was performed with the Google cloud And Goggle My Business API.
- Once obtained Data was cleaned and pre-processed for NLP semantic Analysis using DistilBert.
- Each Review was assigned a positive or negative label and a score
- Word Clouds were generated for all reviews using WordCloud library

## Key findings  
- Over 90% of Element Coffee's 104 reviews had a 5 star rating.  
- The model was able to label 74/78 reviews as 'POSITIVE with an average positive score of 0.999.

- Two reviews were correctly labeled negative out of a total of four negative reviews. Two falsely labeled 'NEGATIVE' reviews were ambiguous and difficult for the model to interpret.


- WordCloud suggests that 'lovely', 'friendly' 'staff' 'warm' 'atmosphere' are top words that occur in the reviews. 

![all_reviews_final](https://user-images.githubusercontent.com/40424244/96500310-931b9080-1246-11eb-9e8a-468be31f775c.png)
Wordcloud generation of all reviews data

## Conclusion  
The Element Coffee Business is doing well with their ratings. Particularly the Atmosphere and friendlieness of the staff is highly revered. Customers use words that suggest a high degree of certainty about their review of the coffee shop.


##  Recommendations  
Using these Data to inform the online store is paramount in the coming times of lockdown and COVID19. It is not certain that the brick and mortar store will remain open therefore feeding these results back into the online presence and website is the best way to proceed.
