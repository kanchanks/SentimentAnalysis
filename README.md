# SentimentAnalysis

### Sentiment Analysis on VADER a rule based dictionary: https://github.com/cjhutto/vaderSentiment

**01_DataSampling.ipynb**- Clean and filter original data to narrow down the scope of the problem (to original tweets containing COVID-19 keywords and originating from EU)
**02_TwitterSentimentAnalysis.ipynb**- Uses VADER dictionary to compute sentiment Score for the filtered tweets.<br>
    Polarity tags based on sentiment scores are assigned as follows:<br>
    - positive sentiment: compound score >= 0.05
    - neutral sentiment: (compound score > -0.05) and (compound score < 0.05)
    - negative sentiment: compound score <= -0.05
**03_DiffusionAnalysis.ipynb**- Counting the replies for each of the original tweets and mapping the total count against the original tweet<br>
**04_Result_Analysis.ipynb**- Computing mean score for each polarity<br>
