# EquityInSentiment
This repo contains code that evaluates racial and gender bias of two NLP cloud services:
Amazon's [AWS Comprehend](https://aws.amazon.com/getting-started/tutorials/analyze-sentiment-comprehend/) and [Google's Google Cloud Natural Language](https://cloud.google.com/natural-language/docs/sentiment-tutorial).

Both show statistically significant racial and gender bias in sentiment rating
on a test corpus [described here](http://aclweb.org/anthology/S18-2005.pdf).

The [EvaluateSentimentScores.ipynb](EvaluateSentimentScores.ipynb) notebook loads the corpus
and runs sentences from the corpus on the Google and AWS services respectively. The
notebook [EvaluateCloudSentimentBias.ipynb](EvaluateCloudSentimentBias.ipynb) then
computes statistical significance of the results and produces a set of visualizations.



