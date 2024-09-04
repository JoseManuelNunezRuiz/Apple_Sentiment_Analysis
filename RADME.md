# Sentiment Analysis of Apple-Related Tweets

## Introduction
In this project, we analyzed apple-related tweets scraped from X with Nitter. The main objective is to understand the general sentiment towards the trademark and explore the most relevant topics, like the new iPhone release.

## Methodology

### Getting Data
200 tweets containing the hashtag #Apple were collected using the Nitter scraper. The data includes the tweet text, date, and metrics of likes and comments.

### Sentiment Analysis
The VADER sentiment analyzer was used to classify tweets into positive, negative, and neutral categories. Additionally, TextBlob was employed to calculate the polarity and subjectivity of the tweets.

### LDA Modeling
Latent Dirichlet Allocation (LDA) was applied to identify the main topics in the tweets. Irrelevant words were removed to obtain a clearer visualization of the topics.

### TF-IDF Analysis
TF-IDF was calculated to determine the most important words in positive and negative tweets. The distribution of terms was visualized through bar graphs and word clouds.

## Findings

- **Sentiment Distribution**: Most tweets are positive, especially towards the iPhone and iOS; however, there is polarization towards the Apple brand, slightly leaning towards the negative side. There is also some discontent about the price and clear rejection towards the Apple Watch..
- **Main Topics**: The main topics identified by LDA include Apple, iPhone, iOS, Amazon, Watch, and Price, which are related to the launch of the new iPhone 16 by Apple.
- **Significant Words**: The words with the highest TF-IDF in positive tweets include Apple, iPhone, Pro, New, 15, Amazon, and 16; while in negative tweets they include Apple, Watch, iPhone, Technology, and iPad.

## Conclusions
The analysis suggests that users have a predominantly positive perception of the iPhone, with a slight preference towards the 15 which is the previous generation. On the other hand, while Apple has the highest positive perception, it also has the highest negative perception, which is more pronounced than the positive one. People reject the Apple Watch in comments and also have a negative feeling about Apple in terms of technology. The most relevant topics and words can provide valuable information to adapt to customers and modify products that are currently rejected, such as the Apple Watch and the iPad; likewise, people want innovations that justify the high costs of the brand.