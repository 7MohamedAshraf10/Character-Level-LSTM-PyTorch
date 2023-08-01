# Character-Level-LSTM-PyTorch
This repository contains an implementation of a character-level LSTM (Long Short-Term Memory) model using PyTorch. The model is trained to generate text one character at a time, allowing it to learn and generate text in the style of the training data.

LSTMs are a type of recurrent neural network (RNN) that are capable of learning long-term dependencies in data. This makes them well-suited for tasks such as text generation, where the generated text should follow the patterns and structure of the training data.

In this project, we train a character-level LSTM model on a large corpus of text. The model learns to predict the next character in a sequence based on the previous characters. Once trained, the model can be used to generate new text by sampling one character at a time from its output distribution.
