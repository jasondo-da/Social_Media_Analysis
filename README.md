# Social Media Sentiments Analysis

![image](https://github.com/jasondo-da/Social_Media_Sentiments_Analysis/assets/138195365/2e065f22-74b1-4722-86f8-ce8af7c19fb9)

## Table of Contents

- [Project Introduction](#project-introduction)
    - [Social Media Sentiments Analysis Jupyter Notebook](#social-media-sentiments-analysis-jupyter-notebook)
    - [Social Media Sentiments Analysis Dataset](#social-media-sentiments-analysis-dataset)
- [Objective](#objective)
- [Analysis Outline](#analysis-outline)
- [Conclusion](#conclusion)

## Project Introduction

This is a Kaggle-sourced dataset used to refine my data analytics skills further and gain more experience in the data science field. In this analysis, I want to gauge social media user behavior and sentiment across various platforms to better understand social media users and how they engage with the platform. The Social Media Sentiments Analysis Dataset documents user interactions with one another through their posts, likes, and reshares across multiple social media platforms. This dataset is a snapshot of user-generated content consisting of text, sentiment, timestamps, usernames, platform used, hashtags, likes, reshares, and user country. 

### Social Media Sentiments Analysis Jupyter Notebook

All codes of Social Media Sentiments Analysis in Jupyter Notebook

Link: [Social Media Sentiments Analysis](https://github.com/jasondo-da/Social_Media_Sentiments_Analysis/blob/main/social_media_sentiments_analysis.ipynb)

### Social Media Sentiments Analysis Dataset

The Social Media Sentiments Analysis Dataset captures a vibrant tapestry of emotions, trends, and interactions across various social media platforms. This dataset provides a snapshot of user-generated content, encompassing text, timestamps, hashtags, countries, likes, and retweets. Each entry unveils unique stories—moments of surprise, excitement, admiration, thrill, contentment, and more—shared by individuals worldwide.

Link: [Original Kaggle Dataset](https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset)

| Columns | Description |
| :------------- | :------------ |
| Text | User-generated content showcasing sentiments |
| Sentiment | Categorized emotions |
| Timestamp | Date and time information |
| User | Unique identifiers of users contributing |
| Platform | Social media platform where the content originated |
| Hashtags | Identifies trending topics and themes |
| Likes | Quantifies user engagement (likes) |
| Retweets | Reflects content popularity (retweets) |
| Country | Geographical origin of each post |
| Year | Year of the post |
| Month | Month of the post |
| Day | Day of the post |
| Hour | Hour of the post |

## Objective

In this analysis, I want to gauge social media user behavior and sentiment across various platforms to better understand social media users and how they interact on the platform.

## Analysis Outline

Before looking at the dataset, there were several interesting questions I wanted to learn more about. Below are the insights I am interested in exploring more:

General User Demographics

a. What are the user’s preferred social media platforms?

b. Which countries contain the largest population of these users?

c. Do different countries have a preferred social media platform?

User Activity

a. Do users prefer to like or reshare posts?

b. Do social media users engage differently on each platform?

c. Which hours are users most active?

d. Which season do users have the highest activity on social media?

e. How has user engagement changed over time?

User Sentiment

a. Is user post sentiment different on each platform?

b. Does user sentiment affect the length of their text posts?

c. Does user sentiment affect likes and shareability?

d. Are there any anomalies in user sentiment throughout the day?

e. How has user sentiment on each platform changed over time?

## Conclusion

General User Demographics:

- The documented users do not have a decisive favorite social media platform with all three platforms having roughly the same number of active users

- The largest markets of active users are from the USA, UK, Canada, Australia, and India

- Most of the active users are from the western countries

User Activity:

- In total, users tend to like posts more than resharing posts, for every two likes there will be one reshare

- The likes-to-reshare ratio is the same across all social media platforms showcasing that this is a social media user behavior and not an anomaly

- Looking at the timestamp from posts, user likes and reshares activity mirror each other with a two-to-one ratio but user activity differs from each platform:

    - Facebook posts frequency starts slow throughout the morning until about 2 pm when the user activity spikes. After 2 pm activity slows down and maintains an elevated level until 7 pm when the daily activity peaks before significantly slowing down by midnight

    - Instagram post frequency is non-existent until 6 am and then users start to slowly increase their activity until 2 pm when we see a large spike recording the daily high in user activity. Instagram user activity slows from its 2 pm peak but remains at a highly elevated level until about 8 pm.

    - Twitter post frequency does not start picking up until about 8 am and consistently increases to 2 pm where they see their first spike in activity. Unlike other social media platforms, Twitter user activity remains high until 8 pm and reaches their daily peak activity at 7 pm

- Looking at the total posts per month for each platform, each platform shows a different number of user activities that differs from season to season

    - Facebook shows signs of peak activity in February and August in addition to high activity in January, June, and September

    - Instagram shows relatively high activity year-round with March, May, October, and December being the exceptions

    - Twitter’s high-activity months include January, February, June, August, and September

- When comparing total social media activity from 2010 to 2023 all three platforms show the same level of user activity. Generally, social media activity started to see significant growth from 2014 to 2019 before seeing exponential growth in 2023

User Sentiment

- When grouping social media post sentiments across all platforms, surprisingly it shows that most posts are posts with positive sentiment by a significant margin

- When looking at post sentiment and text length, there shows that there is a small correlation between negative posts on Twitter being on average shorter than negative posts on other platforms. It also shows that generally positive posts have a wider range of text length than the other sentiments.

- We have also noticed a significant correlation between post likes, shareability, and post sentiment. Negative posts on average see about 20% fewer likes and reshares than neutral and positive posts

- Throughout the day post frequency of each sentiment moves at a similar pace until 5 pm to 8 pm where positive posts see a spike in frequency while neutral and negative post frequency plateaus for the day

- From 2010 to 2016 negative and neutral posts were non-existent indicating that there may be missing data within the dataset. However, in 2023 there is a significant increase in positive post frequency when compared to neutral and negative posts
