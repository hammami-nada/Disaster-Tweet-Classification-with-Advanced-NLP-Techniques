# Sentiment Analysis on Tweets
I developed a machine learning model to classify tweets as either related to real disasters or not.I worked with a dataset of 10,000 hand-labeled tweets.
In the context of emergency situations, Twitter has become a crucial communication tool:the widespread use of smartphones allows people to report emergencies in real-time, prompting various organizations such as disaster relief agencies and news outlets, to programmatically monitor Twitter for relevant information.
Designed a sentiment analysis system to classify tweets into disaster-related or non-disaster-related categories.

Compared various models, including Recurrent Neural Networks (RNNs) and advanced transformers like BERT, RoBERTa, ConvBERT, and BERTweet. Achieved optimal performance with BERTweet, attaining an F1 score of 83.6%. Applied techniques such as tokenization, padding, and fine-tuning to enhance model accuracy and precision. Evaluated model performance using F1 scores and accuracy metrics.

The dataset link:"https://www.kaggle.com/competitions/nlp-getting-started".

Each cell is commented, but if you have any questions please contact me.
## Summary of Results

| Model         | F1 Score | Validation Accuracy | Model Details                           |
|---------------|----------|---------------------|-----------------------------------------|
| **LSTM**      | 0.76923  | ~76.25% to ~79.00%   | Embedding layer, LSTM with dropout      |
| **BERT**      | 0.81734  | ~80.31%              | BERT-base-uncased, fine-tuned with `Trainer` |
| **RoBERTa**   | 0.82960  | ~82.81%              | RoBERTa-base, fine-tuned with `Trainer` |
| **ConvBERT**  | 0.81182  | ~82.02%              | ConvBERT-base, fine-tuned with `Trainer` |
| **BERTweet**  | 0.83634  | ~83.20%              | BERTweet-base, fine-tuned with TensorFlow |



Thank you for your time and have fun!
