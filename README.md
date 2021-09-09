# Amazon-Alexa-Reviews-Python
In recent decades, as online marketplaces have become popular, the online vendors and retailers ask their customers to express their views about the items that they purchased.
During their search for goods, these reviews were taken into account by other users. The industry has therefore found the source of providing the correct product searched by the
consumer on the basis of user feedback using the principle of sentimental analysis. In a business setting, sentiment analysis is extremely helpful as it can help understand 
customer experiences, gauge public opinion, and monitor brand and product reputation. Analysing these opinions can be hard and time consuming for product manufacturers. 

## Problem Statement
Amazon is one of the giants of e-commerce that people use every day for online transactions where thousands of reviews can be read, dropped by other customers on their favorite
items.These reviews provide useful views on a product, such as its property, quality and recommendations, which are valuable. This is not only good for buyers, but also supporting
sellers who produce their own items to better understand the customers and their needs. This project explores the issue of sentiment classification for online reviews using
supervised methods to evaluate the overall customer reviews by categorizing them into positive and negative feelings.Apart from quantitative reviews (which are mostly skewed), 
amazon also records qualitative reviews. The objective is to assess those text reviews and determine whether they are negative or positive.

## Dataset
The first step for conducting the research includes data collection for training and testing the classifiers. The dataset found is a tab-separated values (TSV) file. The TSV file can easily be converted into an excel format, to comprehend the data. The data contains 3150 samples and 5 features. The features are mentioned below :
- Rating 
- Date
- Variation
- Verified Reviews
- Feedback

## Exploratory Data Analysis
- Distribution of Ratings for Alexa
- Distribution Of Variation in Alexa
- Distribution of feedback from Alexa
- Distribution of length reviews
- Variation VS Ratings
- Variation vs Length of Ratings
- Tokenization

## Natural Language Processing 
- Corpus
- Bag of Words

## Model Training
- Decision Tree
- Random Forest
- Support Vector Machine

## Results
<p align="center">
  <img src="https://github.com/rc754/rc754/blob/main/Images/result-table.PNG" width="600"/>
</p>

In conclusion, the results show the vast majority of reviews written by Amazon’s Alexa customers were highly positive. Overall, 87% of the customers gave Alexa at least 4- star
ratings. When it comes to positive and negative feedback scores, 91.8customers have given a positive feedback, and only 8% of customers have given a negative feedback to Alexa. This shows that Alexa customers are very pleased with their purchase. Only a small percentage had some kind of complaint towards Alexa or did not like the product. The different model variations of Alexa that have darker color tones (e.g. Black Dot model) were ranked more popular against models with lighter color tones (e.g. White model). For the White model, besides being one of the least popular models, it is also among the models with the most negative ratings.
