# Analyzing_SocialMedia_Engagement_Trends
# Project Overview:

This project analyzes social media engagement trends across platforms such as Facebook, Instagram, and Twitter. The goal is to examine how different attributes—such as post type, posting time, caption, hashtags, likes, comments, shares, and sentiment score—affect user engagement.

By leveraging Python and Pandas, this analysis provides valuable insights into which types of posts perform best and how various factors influence engagement metrics.

# Dataset:

The dataset used in this project contains key attributes of social media posts, including:

post_id: Unique identifier for each post
platform: Social media platform (Facebook, Instagram, Twitter)
post_type: Type of post (image, video, text, poll, carousel)
post_time: Timestamp of the post
caption: Text caption of the post
hashtags: Hashtags used in the post
likes: Number of likes received
comments: Number of comments received
shares: Number of times the post was shared
caption_length: Length of the caption
num_hashtags: Number of hashtags used
post_hour: Hour of the day the post was made
post_day: Day of the week the post was made
sentiment_score: Sentiment of the post (positive, neutral, negative)
 Dataset Source: The Power Of Social Media Engagement - Kaggle

# Analysis Performed:

The Jupyter Notebook includes the following steps:

Data Exploration
Displaying the first and last 10 rows of the dataset
Checking column data types
Identifying missing/null values
Generating summary statistics (number of rows, columns, and data distributions)
Data Cleaning
Handling missing values
Converting data types where necessary
Filtering unnecessary columns
Exploratory Data Analysis (EDA)
Distribution of engagement metrics (likes, comments, shares)
Analyzing the impact of post type, post hour, and sentiment score on engagement
Finding patterns in hashtags and captions
Sentiment Analysis
Examining how post sentiment (positive, neutral, negative) affects engagement

# Technologies Used:

Python (Data analysis and manipulation)
Pandas (Handling and processing datasets)
Jupyter Notebook (Interactive analysis)
