
# News Sentiment Analysis

This project fetches recent news headlines (query = 'data science') and classifies them as Positive / Neutral / Negative using TextBlob sentiment polarity.

## Files
- news_headlines_raw.csv — raw headlines fetched
- news_sentiment_results.csv — final results (headline, polarity, sentiment)
- news_sentiment_notebook.ipynb — this notebook

## How to run
1. Open the notebook in Colab.
2. Run cells from top → bottom.
3. The CSV outputs will be stored in `/content/drive/MyDrive/datasets/news_project/`.

## Sample output
Top sentiments counts:
{'Neutral': 49, 'Positive': 25, 'Negative': 6}
