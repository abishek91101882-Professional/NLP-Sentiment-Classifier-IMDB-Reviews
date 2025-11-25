**NLP Sentiment Classifier — IMDB Movie Reviews
**
Bi-LSTM | Bi-GRU | CNN-1D | Custom Embeddings | TensorFlow

A deep learning–based sentiment analysis system built on the IMDB movie review dataset. This project benchmarks multiple neural architectures (Bi-LSTM, Bi-GRU, CNN-1D) to classify reviews as positive or negative, and explores how preprocessing, embeddings, and regularization influence model performance.

**Project Highlights**
-Implemented three advanced architectures for sentiment classification:
-Bi-LSTM (Bidirectional LSTM)
-Bi-GRU (Bidirectional GRU)
-CNN-1D (Convolutional Neural Network)
-Designed a custom text preprocessing pipeline including tokenization, stop-word removal, and sequence padding.
-Integrated pre-trained embeddings and experimented with custom-trained embeddings.
-Achieved 90%+ test accuracy after hyperparameter tuning and regularization (Dropout + EarlyStopping).
-Performed model benchmarking to compare training time, accuracy, and generalization performance.

**Models Implemented**
**1️. Bidirectional LSTM**
-Captures long-range dependencies
-Performs best on longer, complex sentences
-Achieved the highest accuracy among all models

**2️. Bidirectional GRU**
-Faster training compared to Bi-LSTM
-Slightly lower accuracy but better runtime efficiency

**3️. CNN-1D**
-Captures local n-gram features
-Lightweight and fast
-Performs well with optimized filter sizes
