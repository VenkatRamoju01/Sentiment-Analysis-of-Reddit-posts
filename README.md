# Reddit Sentiment Analysis on ChatGPT Discussions

This notebook performs a comprehensive analysis of Reddit posts and comments related to ChatGPT. Users can expect to find the following key components:

1. **Data Collection**:
   - Importing and utilizing Reddit API credentials.
   - Importing necessary modules.
   - Calling the Reddit API to retrieve posts and comments data.

2. **Post & Comment Analysis**:
   - **Exploratory Data Analysis (EDA)**:
     - Extracting posts data and cleaning date formats.
   - **Visualizations**:
     - Analyzing the number of posts across different months.
     - Visualizing engagement metrics over time.
   - **Comments Analysis**:
     - Extracting and joining comments with their respective posts.

3. **Word Clouds**:
   - Generating word clouds to identify the most frequently used words:
     - Post title word cloud.
     - Comment word cloud.
     - Post title word cloud segmented by year.

4. **Sentiment Analysis**:
   - The sentiment analysis is conducted using a pre-trained model from the Hugging Face model hub. The model, specifically trained for analyzing sentiment in tweets.
   - This model classifies comments and posts into sentiment categories (Positive, Negative, Neutral) and visualizes sentiment distribution for both posts and comments using pie charts.
  
5. **Engagement Analysis**:
   - Analyzing engagement metrics by post type.
   - Evaluating engagement based on post sentiment.

This notebook aims to provide insights into user sentiment and engagement trends within the ChatGPT Reddit community, utilizing visualizations and word clouds to enhance understanding.
