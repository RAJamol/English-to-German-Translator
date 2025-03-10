
# German to English Translator

In this project, I implemented a sequence-to-sequence (seq2seq) model utilizing an encoder-decoder architecture to translate German sentences into English. The encoder processes the input German sentence, converting it into a fixed-length context vector, which the decoder then uses to generate the corresponding English translation.



## Features

Preprocessing: Tokenization, padding, and embedding for input text.

Model: Seq2Seq with an LSTM based encoder-decoder.

Training: Supervised learning with a cross-entropy loss function.

Inference: Translating German sentences into English.
## Dataset

The model is trained on a bentrevett/multi30k dataset
## Note

This project is intended to showcase practical knowledge of the seq2seq encoder-decoder architecture for translation tasks. Training the model for additional epochs may yield improved translation accuracy. 
