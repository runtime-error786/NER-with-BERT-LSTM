 
# NER with LSTM: 
A custom NER model built with PyTorch that leverages an LSTM (Long Short-Term Memory) network for sequence labeling. The dataset is tokenized, padded, and encoded into word indices, and the LSTM processes these word embeddings to predict NER tags. Training is done using cross-entropy loss, and evaluation involves generating classification metrics like precision, recall, and F1-score. The LSTM model is lightweight and designed for those learning to build sequence models from scratch.

# NER with BERT: 
A more advanced approach using a pre-trained BERT model fine-tuned for token classification. The transformers library is used for tokenization and model loading. Tokens and NER labels are aligned to handle subwords, and the model is fine-tuned using the Trainer API for efficient training and evaluation. This approach leverages BERT's ability to understand contextual word representations, yielding better performance compared to traditional LSTMs.
