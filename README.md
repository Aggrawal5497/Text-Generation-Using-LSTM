# Text-Generation-Using-LSTM

## Text Generation
Natural-language generation (NLG) is the aspect of language technology that focuses on generating natural language from structured data or structured representations such as a knowledge base or a logical form. Psycholinguists prefer the term language production when such formal representations are interpreted as models for mental representations.

## Model Used
Long short-term memory (LSTM) units (or blocks) are a building unit for layers of a recurrent neural network (RNN). A RNN composed of LSTM units is often called an LSTM network. A common LSTM unit is composed of a cell, an input gate, an output gate and a forget gate. Source wikipedia.
RNNs can be used to make predictions, or to learn from sequential data and generate similar data.
The idea is to train the RNN with many sequences of words and the target next_word.We don’t actually send the strings, but a vectorized representation of the word inside a dictionary of possible words (more on that later). The idea is that after many epochs the RNN will learn “the style” of how the corpus is written, trying to adjust the weights of the network to predict the next word given a sequence of the N previous words.

## Text Corpus
Title: The Time Machine

Author: H. G. Wells

Source : https://www.gutenberg.org/files/35/35-0.txt

## References
- https://www.gutenberg.org/files/35/35-0.txt
- https://en.wikipedia.org/wiki/Natural-language_generation
- https://medium.com/coinmonks/word-level-lstm-text-generator-creating-automatic-song-lyrics-with-neural-networks-b8a1617104fb
