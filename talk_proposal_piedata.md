# Talk Proposal: PieData

## General

### Submission Title

PieData - Text Mining on Cake Recipes

### Submission Type

Talk (30 min.)

### Abstract

This talk summarizes a text mining project applied to 40,000 cake recipes. The focus lies on generating numerical embeddings from ingredients and recipe instructions and applying supervised learning to predict the cake ratings on a five point scale.

### Description

Everbody enjoys a slice of delicious cake. But how does one prepare good cake? And how can you avoid your freshly baked pie to be too dry, dense or tough? In this talk, we will learn about baking objectively delicious cake by analyzing more than 40,000 cake recipes and user ratings from a large German recipe platform. During the presentation, we will cover all steps involved in a text mining project that are:

1. Sourcing and describing the data.  
2. Cleaning and normalizing the text.  
3. Converting text into meaningful topics.  
4. Engineering and selecting features.  
5. Fitting a regression model to the average user rating.  
6. Evaluating the results.

The audience will learn about general natural language processing tools, such as term frequency–inverse document frequency and singular value decomposition. Further, we will demonstrate how to integrate all these components into a single machine learning pipeline, using scikit-learn.

### Notes



### Don't record this talk

No

### Additional Speaker

None

## Questions

### Domains

Data Science, Natural Language Processing, Machine Learning, Visualisation, Statistics, Data Mining / Scraping, Use Cases

### Domain Expertise

Some

### Python Skill Level

None

### Link to talk slides

tba

### Abstract as a tweet

Do you love #Pie as much as you love #Data? Join Jan's talk about text mining cake recipes and get a taste of natural language processing with #ScikitLearn.

### Public link to supporting material

tba

### Notes for reviewers only

- The data was extracted from chefkoch.de, using a scraper written in Python. This means that the raw data is mostly in German. However, all necessary information for this talk will be translated to English.
- I checked chefkoch.de's terms and conditions (AGB), which does not specify whether data can be scraped and/ or shared with others. I am no expert on this subject, but I believe that scraping and sharing for a non-profit, educational purpose lies within their AGBs. I have also attached a copy of their AGBs from June 2019.
- If time allows, we will also briefly cover more advanced topics, such as ELMO and BERT.
