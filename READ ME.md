# Canadian Federal Election 2019 Twitter Analysis

This project focuses on analyzing tweets related to the 2019 Canadian federal election. On October 21, 2019, the 43rd Canadian Parliament was elected, and this project aims to gain insights from the social media platform Twitter regarding the election. Twitter is widely used by political leaders, journalists, government agencies, political parties, civil societies, and lay citizens to share their ideas, thoughts, motives, and election agendas.

## Problem Statement
With the abundance of tweets about the Canadian election, it is challenging to manually analyze all the text to identify trending topics, people's sentiments, leaders' approaches, and the problems highlighted by the public. To address this, natural language processing (NLP) tools and techniques are employed to automatically extract valuable information from raw text data.

## Dataset Description
The dataset used in this project contains tweets about the Canadian election in 2019. It is sourced from Twitter and provided in JSON file format. The dataset comprises the following 29 columns:

1. Created at (timestamp indicating the tweet's creation date)
2. Id (tweet ID)
3. Id_str
4. Full_text (the main text of the tweet)
5. Truncated
6. Display_text_range (range of text in the tweet)
7. Entities (hashtags in the tweet)
8. Source (the source of the tweet)
9. In_reply_to_status_id
10. In_reply_to_user_id_str
11. In_reply_to_screen_name
12. User (attributes of the user account)
13. Geo (tweet's geolocation)
14. Coordinates
15. Place
16. Contributors
17. Is_quote_status
18. Retweet_count
19. Favorite_count
20. Favorited
21. Retweeted
22. Lang (language of the tweet)
23. Quoted_status_id
24. Quoted_status_id_str
25. Quoted_status_permalink
26. Quoted_status
27. Possibly_sensitive
28. Retweeted_status
29. Extended_entities

## Methodology
The manuscript outlines the automated analysis of raw tweet text related to the Canadian federal election 2019. The tweets are extracted using the Twitter API and stored in a JSON format file, which is then loaded into a Python dataframe. Preprocessing techniques are applied to the tweet text, including the removal of stop words and other unnecessary words. Sentiment analysis is performed to extract the sentiment of the tweets. The most common words are extracted from the tweets, revealing that immigration, refugees, and borders were the main topics of discussion. Lastly, the analysis focuses on different types of actors involved in the election tweets campaign, such as lay citizens, organizations, politicians, and journalists. The sentiment of their tweets is calculated to determine which actors played a positive role in the election and which spread hate speech.

## Project Structure
The project follows the following structure:

1. Introduction
   - Problem statement
   - Dataset description

2. Data Collection and Preprocessing
   - Extraction of tweets using the Twitter API
   - Loading and structuring the data in a Python dataframe
   - Text preprocessing techniques

3. Sentiment Analysis
   - Extracting sentiment from tweet text
   - Determining overall sentiment distribution

4. Trending Topics
   - Identifying the most common words/topics in the tweets

5. Analysis of Different Actors
   - Categorizing actors based on their account types
   - Analyzing sentiment by actor type

6. Discussion
   - Evaluation and interpretation of results
   - Insights and implications

## Conclusion
The automation of text analysis for tweets related to the Canadian federal election 2019 provides valuable insights into the sentiments, trending topics, and the roles played by different actors. The

 project enhances our understanding of public sentiment, highlights key election topics, and identifies actors promoting positive engagement or spreading hate speech during the election campaign.

For further details, please refer to the project code, analysis results, and discussions.

If you have any questions or require additional information, please feel free to reach out.

Thank you for your interest in this project!
