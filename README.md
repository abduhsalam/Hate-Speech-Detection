# The Dataset for Hate Speech Detection in Indonesian
<b>(Dataset untuk Deteksi Ujaran Kebencian dalam Bahasa Indonesia)</b>

<b>Dataset</b>
The dataset is a two columns data of: label - tweet, consist of 713 tweets in Indonesian.
The label is Non_HS or HS. Non_HS for "non-hate-speech" tweet and HS for "hate-speech" tweet.
- Number of Non_HS tweets: 453
- Number of HS tweets: 260
Since this dataset is unbalanced, you might have to do over-sampling/down-sampling in order to create a balanced dataset.<br>
The dataset may be used freely, but if you want to publish paper/publication using the dataset, please cite this publication:

Preproceesing
- Case Folding (Lowercase, Remove Number, remove punctuation, whitespaces)
- Tokenization
- Stopword Removal
- Stemming
