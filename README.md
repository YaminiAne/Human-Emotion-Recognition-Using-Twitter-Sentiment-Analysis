# Human-Emotion-Recognition-Using-Twitter-Sentiment-Analysis

> ![Sentiment Analysis](https://user-images.githubusercontent.com/83130336/188488944-4e879e77-0c56-4bb8-bf83-844e2fcdca7d.jpg)

## (1) Introduction
With the outbreak of various social media platforms, people these days tend to
express their views, opinions, reviews
or in general make conversations with others all across the world through such platforms. Twitter is one of the most 
widely used social media platform that poeple use. The main objective of this project is to predict and understand the emotion behind a given text. This task is achieved by creating a machine learning model that is trained and tested by making it predict whether the sentiment surrounding a Twitter tweet is positive or negative. Classifying and understanding the human emotion in any given text can actually be very helpful in many ways.

## (2) Business Problem
<p>Given a text, classify whether it has a positive or a negative emotion. </p>
It is clear that this is a binary classification problem .

## (3) Dataset
> https://www.kaggle.com/datasets/kazanova/sentiment140 </br>
<p> Inorder to make the model capable enough to predict the sentiment, we train it using  dataset containing 1,600,000 tweets. </p>

Shape of the dataset : (1600000,6)

Attributes:
- target: the polarity of the tweet (0 = negative 4 = positive)
- ids: The id of the tweet
- date: the date of the tweet
- flag: The query (lyx). If there is no query, then this value is NO_QUERY.
- user: the user that tweeted 
- text: the text of the tweet 
<p> Here, we just need the 'text' and 'target' columns for the model.</br>
'text' -----> independent attribute </br>
'target' ---> dependent attribute </p>

## (4) Real Time Applications
By identifying the sentiment behind the tweets can be beneficial in many ways. For instance,
- Businesses can understand the customer needs, their likes and dislikes.
  Accordingly, further marketing strategies can be framed, product improvements can also be done.
- Political parties can keep a track of the political opinion of the voters.
    
## (5) Implementation
The project has been implemented using Python </br>
It is available in this repository </br>
> [Jupyter Notebook](https://github.com/YaminiAne/Human-Emotion-Recognition-Using-Twitter-Sentiment-Analysis/blob/main/Human%20Emotion%20Recognition%20Using%20Twitter%20Sentiment%20Analysis.ipynb) </br>

Hope this repository was helpful! </br>
Do star the repository incase you liked it. </br>
Thank You :)
