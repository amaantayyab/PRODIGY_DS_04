# Tweet Analysis Project

This project analyzes a dataset of tweets to understand engagement metrics such as likes, retweets, and sentiment for different entities (brands).

## Dataset Description

The dataset consists of 1000 entries with the following columns:

- **tweet_id**: Unique identifier for each tweet (integer).
- **entity**: Brand or entity associated with the tweet (string).
- **sentiment**: Sentiment associated with the tweet (`positive`, `negative`, `neutral`) (string).
- **tweet_content**: Text content of the tweet (string).
- **user_name**: Username of the user who posted the tweet (string).
- **location**: Location associated with the user (string).
- **retweets**: Number of retweets for the tweet (integer).
- **likes**: Number of likes for the tweet (integer).
- **date**: Date when the tweet was posted (string, formatted as YYYY-MM-DD).
- **source**: Source from which the tweet was posted (`web`, `mobile`, etc.) (string).

## Analysis Conducted

### Most Liked and Most Hated Brands

Visualized and identified the brands that received the highest number of likes and dislikes based on sentiment analysis.

### Most Active User

Identified the user who posted the highest number of tweets and their engagement metrics.

### Viral Tweets

Identified tweets that went viral based on the highest number of retweets and likes.

### Source of Tweets

Analyzed the distribution of tweets based on their source (web, mobile, etc.).

## Conclusion

Summarize the findings from the analysis and any insights gained from the dataset.

## Installation

Ensure you have Python 3.x installed. Install the required libraries using pip:

```bash
pip install pandas matplotlib
