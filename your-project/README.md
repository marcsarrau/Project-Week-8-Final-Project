<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Sentiment Analysis on Skincare
*[Marc Sarrau Orus]*

*[Data Analytics Full Time Barcelona Oct2020]*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The purpose of this project is to have an understanding and predict if sentiment analysis in social media can be performed with certainty.

## Hypotheses / Questions
* What does people think of skincare?
* Does it really work? Is there a positive or negative opinion?
* How is sentiment analysis algorithm interpreting human feelings at a large scale?
* Can I do a better model to predict the coefficient of negativity?

## Dataset
I have scraped more than 12,000 tweets of the words and hashtags skincare, acne, maskne, accutane and skincare routine. 
* Note: this repo only includes the jupyter file for one of the words. The same process has been repeated for all the words mentioned before 
and have helped reach a common conclusion. 

## Cleaning
I have followed the usual pattern: removing stopwords, stemming, lemmatizing, tokenizing and making a bag of words and perform sentiment analysis

## Analysis
* By displaying on Tableau the most repeated words we can get a glimpse of the sentiment of the actual topic.

## Model Training and Evaluation
I have conducted 3 different models: Linear Regression, Random Forest Regressor and Decision Tree. The best results were achieved with the Decision Tree Regressor predicting the negativity coefficient. 

## Conclusion
* There is room for word classification improvement and NLP should interpret jargons.
* There is a large applicability of the model accross the industry and also, it would be ideal to better know the public opinion.

## Future Work
Create a model that classifies positive and negative comments of different sectors and topics and that uses reinforcement learning to improve it's 
positivity and negativity scores.

## Workflow
1. Learn how the Twitter API works
2. Create the DataFrame
3. Clean all the tweets
4. Get the sentiment score (positivity/negativity)
5. Extract insights from the most frequently used words
6. Test and train a new model to predict sentiment score with new tweets
7. Evaluate its accuracy with the root MSE
8. Conclusions

## Organization
I organized the project by doing a trello board (link below) and calendar with a task for each day, and several meetings with my mentor. 

The repository looks like a template or draft where you can see the process of the tweet analysis. This process has been repeated with other
words used in the skin care community 

## Links
Here you can find all the links to my project.

[Repository](https://github.com/marcsarrau/Project-Week-8-Final-Project)  
[Slides](https://docs.google.com/presentation/d/1kN7LJYTdvZUNVTPeE_nC8qZ1eh8KkLE6T0Qb8pLM3eA/edit?usp=sharing)  
[Trello](https://trello.com/b/ZLXR7Ys0/sentiment-analysis-on-skincare)  
