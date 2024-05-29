# Covid-19 Vaccine Sentiment Analysis

Analyze and visualize sentiment from vaccination-related tweets using various NLP techniques and libraries. This project includes data preprocessing, sentiment analysis with VADER, and visualization using Matplotlib, Seaborn, and WordCloud.

## Features

- Data cleaning and preprocessing
- Sentiment analysis using VADER
- Visualizations with Matplotlib, Seaborn, and WordCloud

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/vaccination-tweets-sentiment-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd vaccination-tweets-sentiment-analysis
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure your dataset (`vaccination_tweets.csv`) is in the project directory.
2. Run the analysis script:
    ```bash
    python sentiment_analysis.py
    ```

## Example Analysis

This project performs the following steps:
1. **Data Preprocessing**: Clean and preprocess the tweets by removing unwanted characters, URLs, and converting text to lowercase.
2. **Sentiment Analysis**: Use the VADER sentiment analysis tool to evaluate the sentiment of each tweet.
3. **Visualization**: Create various plots to visualize the distribution of sentiments and the most common words in positive and negative tweets using Matplotlib, Seaborn, and WordCloud.

## Visualizations

### Distribution of Sentiments

- **Sentiment Analysis Distribution**: Kernel density plots showing the distribution of positive, neutral, and negative sentiments.
- **CDF of Sentiments**: Cumulative distribution functions (CDF) for positive, neutral, and negative sentiments.

### Word Clouds

- **Most Positive Tweets**: A word cloud highlighting the most common words in the most positive tweets.
- **Most Negative Tweets**: A word cloud highlighting the most common words in the most negative tweets.

## Contributing

Feel free to fork this project and make your own enhancements. Pull requests are welcome.

## License

This project is licensed under the MIT License.
