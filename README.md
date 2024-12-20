# Suicide detection

Contents

1. Data analysis\
1.1. Basic statistics for unprocessed data\
1.2. Word frequency statistics for unprocessed data
2. Preprocessing\
2.1. Text sanitization\
2.2. Text tokenization\
2.3. Text normalization\
2.4. Stop word removal\
2.5. Word statistics for cleaned data\
2.6. Bigrams for processed text\
2.7. Finding linguistic patterns\
2.8. Drop rows with less than 4 tokens\
2.9. Train-test split\
2.10. Text vectorization (baseline)
3. Evaluation methodology\
3.1. Cost matrix and custom scoring function\
3.2. Performance metrics
4. Baseline model\
4.1. Multinomial naive bayes\
4.2. Unigrams and bigrams\
4.3. Extra features (VADER sentiment, Flesch ease, Entropy Scaling)\
4.4. Smaller vocabulary
5. Random forest classifier\
5.1. Smaller vocabulary\
5.2. Larger vocabulary
6. TPOT
7. LSTM (Keras and Tensorflow)\
7.1. Word embeddings\
7.2. GloVe embeddings
8. Transformers\
8.1. DistilBert
9. Evaluate on unseen data\
9.1. Baseline model (MNB) evaluation\
9.2. LSTM + GloVe embeddings evaluation\
9.3. Transformers: DistilBert evaluation
