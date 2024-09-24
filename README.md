# DS-4002-Project-1
First Data Science Project for DS 4002


Research Question: How do the sentiment scores of tweets about Biden and Trump during the 2020 presidential election differ, and are there any specific keywords associated with each candidate? 

Our Motivation: 
Social media has become a powerful platform in shaping news, communication, and public opinion, allowing both politicians and individuals to freely express their views. As we approach the 2024 presidential election, we believe that examining social media’s role during the 2020 election can provide insights into how political opinions intersect with social media. By analyzing whether tweets about Joe Biden and Donald Trump were predominantly positive or negative, and identifying the major topics of discussion, we can reveal how public sentiment was formed and how it might impact future elections. Current research indicates that social media is generally seen as effective in raising awareness, shifting opinions, and influencing policy decisions [3]. Thus, this highlights the importance of analyzing social media data to better understand public opinion trends.

Our Modeling Approach:
Import and preprocess CSV files containing tweets mentioning Trump and Biden this was obtained from: 
"https://www.kaggle.com/datasets/manchunhui/us-election-2020-tweets/code" - it was too large to upload as a file onto GitHub
Conduct initial exploratory data analysis (EDA) and create visualizations
Perform sentiment analysis using the VADER package in python 
Compare average sentiment scores between candidates and determine whether the differences are statistically significant
Identify frequently mentioned words associated with each candidate using Term Frequency - Inverse Document Frequency (TF-IDF)

Data Set Establishment Details:
Goal: The data set was taken from tweets mentioning Trump and Biden during the 2020 U.S. presidential election, collected by using the Twitter API (statuses_lookup) and snsscrape to capture relevant keywords. This data was then exported into a CSV file and subsequently loaded into python for sentiment analysis using the VADER package. 

Summary of Data set: 
970919 rows × 21 columns (Trump), 776886 rows × 21 columns (Biden)
10/15/20 to 11/4/20 (Trump), 10/15/20 to 11/7/20 (Biden)
