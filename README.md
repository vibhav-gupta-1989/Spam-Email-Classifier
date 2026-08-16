# Spam-Email-Classifier

- Developed a machine learning–based spam email classifier using the SpamAssassin corpus.
- Implemented end-to-end email preprocessing, including HTML parsing, URL/number normalization, punctuation removal, lowercasing, and Porter stemming, followed by word-frequency feature extraction.
- Trained a Random Forest classifier and evaluated it using 5-fold cross-validation, achieving 95.5% mean accuracy.
- Optimized the classification threshold using cross-validated predictions, selecting 0.45 based on the best F1 score.
- On the held-out test set, the classifier achieved 97.3% precision and 96.0% recall, demonstrating strong performance in distinguishing spam from legitimate emails.
