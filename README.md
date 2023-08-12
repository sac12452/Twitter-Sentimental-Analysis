# Twitter-Tweets-Sentiment-Analysis
#  <img src = "https://res.cloudinary.com/qna/image/upload/v1635170410/sentiment-points.a502b2c_pyfy2i.png" width = 500></center>

#
##  <h> Analysis of Twitter's User's Sentiments regarding Twitter's Services with Machine Learning and Python (Pandas, NLTK, RE, Seaborn, Matplotlib, NumPy etc)

#
##  <h>  The Project is aimed to provide an analysis of the Sentiments of the Users of Twitter Social Media Platform using Machine Learning Models like Logistic Regression,Decision Tree and Random Forest Model based upon their Ratings and Reviews. The Project's objectives were to build a ML Model that can accurately predict the Sentiments (Positive/Negative) of the users on the basis of the Ratings and the content of the Reviews provided by it's users. The aim was to assist the Social media platforms with the information that they can use to formulate their strategy in order to enhance the User's satisfaction and expand their user base. Additionally, different ML Models have been compared on the basis of their Accuracy Score and other Key Metrics, to find out the best fit model for the task. Moreover, it aimed to reveal some of the dataset's hidden insights. The Data Cleaning was done with Pandas. The ML Models were built with NLTK, RE and Pandas, whereas the analysis of the data has been done with Pandas and visualisation library, Seaborn..




<br>
<br>
<p align="center"><a><img src="https://forthebadge.com/images/badges/built-with-love.svg"><img src="https://forthebadge.com/images/badges/made-with-python.svg"></a></p>

#  <img src="https://user-images.githubusercontent.com/106439762/181935629-b3c47bd3-77fb-4431-a11c-ff8ba0942b63.gif" width="48" height="48"> **User's Manual**

| Files| Description |
| ------------- | ------------- |
| **Twitter(python file)** | This file contains the Python codes of the Suitable structuring of the Data, Data Cleaning and Exploratory Analysis parts, ML model creation. |
| **Twitter(csv_file)**  | This file provides the raw data for the project .  |
<br>


#  <img src=https://user-images.githubusercontent.com/106439762/178428775-03d67679-9aa4-4b08-91e9-6eb6ed8faf66.gif  width="48" height="48"> Analysis
   
    
    o Analysed the Accuracy Scores of Different ML Models for predicting the Sentiments.
    
    o	Also analysed the F1 Scores, Precision Scores and Recall Scores of Different ML Models by creating their Classification Reports.
     
    o	Performed comparison analysis to find out the Best Fit Machine Learning Model suitable for this task.
  
    o	Analysed the relationship between the sentiments and ratings of the users.

<br>

# <img src="https://user-images.githubusercontent.com/106439762/181937125-2a4b22a3-f8a9-4226-bbd3-df972f9dbbc4.gif" width="48" height="48" > Quick Start

    1. Started with cleaning the Data using Pandas by Dropping the Duplicates and Null values.
    
    2. Created a new Data Frame with only relevant columns out of the initial Data Frame.
 
    3. Also Replaced values in Ratings columns to Numbers based on their Intensity and exported the Cleaned data as CSV to use it further for Sentimental Analysis.
    
    4. Imported the Cleaned data in another ipynb file for Sentimental Analysis. 
    
    5. Performed Sentiment Intensity Analysis and based on it's score, categorized the Data as Positive or Negative and made a column out of it in the Data Frame and performed analysis on it.
    
    6. Removed special charcters and stop words present in the text and performed Vectorization (feature extraction) on it.
   
    7. Built different ML models like Logistic Regression, Decision Tree and Random Forest and compared them on the basis of their Accuracy Score and other Key Metrics, to find out the best fit model for the task.

   
<br>

# <img src="https://user-images.githubusercontent.com/108053296/185756908-fbb62168-d923-48f2-992f-b8e2fde848fe.gif" width="48" height="48" > Insights
   
1:-In this data, we have more than 25% positive tweets

2:- We have more then 27% negative tweets.

3:- Combination of Neutral and Irrelevant tweets is more then 40%
  
<br>

# <img src="https://user-images.githubusercontent.com/108053296/185756908-fbb62168-d923-48f2-992f-b8e2fde848fe.gif" width="48" height="48" > Findings
 
1:- From all these wordclouds of different classes, we can "WILL" is the common words used

2:- From positive sentiment wordclouds, we can see that "WINDOWS","IDEA" are the most common words used

3:- From negative sentiment wordclouds, we can see that "LIFE","CAME","BIGGEST" are the most common words used

4:- From neutral sentiment wordclouds, we can see that "ROCK","CC","NVIDIA" are the most common words used

5:-From Irrelevant sentiment wordclouds, we can see that "CONCEPTS","LANDA","MULTIMODAL" are the most common words used


   
   <br>
   
   #  <img src=https://user-images.githubusercontent.com/106439762/178803205-47a08ce7-2187-4f96-b301-a2b68690619a.gif width="48" height="48" > Metrics
![pyhton-pandas](https://user-images.githubusercontent.com/106439762/177094844-d74edfa1-823d-4f17-8d94-3600e058cf1e.svg)
   
1- The Accuracy Score of the Logistic Regression Model built for predicting Sentiments of the Users is found around 80%.

2- The Accuracy Score of the Decision Tree Model built for predicting Sentiments of the Users is found around 79.53%.

3- The Accuracy Score of the Random Forest Model built for predicting Sentiments of the Users is found around 91.04%.


<br>

# <img src="https://user-images.githubusercontent.com/108053296/185756908-fbb62168-d923-48f2-992f-b8e2fde848fe.gif" width="48" height="48" > Challenges

1 - Tweets often contain slang, abbreviations, emojis, and misspellings, making it challenging for traditional natural language processing (NLP) models to accurately interpret the sentiment.

2 - Twitter is notorious for the use of irony and sarcasm, which can be difficult for models to identify, as these expressions might be misinterpreted by sentiment analysis algorithms.

3 - The distribution of sentiments (positive, negative, neutral) in Twitter data can be imbalanced, with neutral tweets often being the most common. This can impact model training and evaluation

4 - Sentiments can change rapidly due to breaking news, events, or trends, which can challenge models that lack the ability to capture temporal dynamics

5 - Traditional sentiment analysis models might not perform well on Twitter data without proper adaptation. Transfer learning and fine-tuning techniques might be necessary.
   
   
   <br>
   
   
   #  <img src=https://user-images.githubusercontent.com/106439762/178803205-47a08ce7-2187-4f96-b301-a2b68690619a.gif width="48" height="48" > Future Scope
   
   <B> The aim of the Project is to: </B>
   
   1. Assist the Social media platforms with the Information that they can use to formulate their strategy in order to enhance the User's satisfaction.
   
   2. Advise the social media platforms on their relationships with their users and help them in expanding their user base.
   
   3. To provide the social media platforms a tool for keeping track on their User's sentiments.
   
   
   
    
