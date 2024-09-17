

This project demonstrates an end-to-end implementation of a Transformer model based on the "Attention Is All You Need" research paper. The model is designed to predict tokenized outputs from a given sentence. The project involves building key components of the transformer architecture, including positional encoding, multi-head self-attention, and feed-forward layers.

The core features of the project include:
- **Positional Encoding**: A mechanism to add information about the position of words in the input sentence, helping the model distinguish between words based on their position.
- **Multi-Head Attention**: The model uses multi-head attention to attend to different parts of the input sentence and learn relationships between words.
- **Feed-Forward Networks**: Each encoder layer includes a feed-forward network to process the input further after attention is applied.
- **Model Training**: The transformer is trained to learn word relationships from a given sentence using Cross Entropy Loss and the Adam optimizer.
- **Sentence Prediction**: After training, the model predicts the next set of tokens for the input sentence. The model can be further fine-tuned for more complex tasks.

In this project, the sentence "My Name is Chandrashekhar Subhash Ghanokar" is tokenized and used to train the model, showcasing a simple but powerful demonstration of how transformers work for language tasks.
