## ABOUT

In this project distand supervision tasks were conducted.

Namely, tweets from twitter.com were classified by 8 emotion classes (anger, disgust, fear, joy, sadness, surprise, anticipation, trust) using distant supervision method. For that noisy labels, emoji-emotion mappings, were derived from the [labeled corpus](http://github.com/Aisulu/emoji2emotion).
Corpus was collecting using an [annotation app](https://github.com/Aisulu/voting_app).

First, tweet texts were converted into word embeddings. After that 3 tasks were implemented:
- Multiclass classification
- Multioutput classification
- Multioutput-multiclass regression

using classifiers from scikit, like:
- SGD
- Random Forest
- Nearest neighbors
- Naive Bayes

and then visualised as heatmaps.
