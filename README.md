# rnn-arxiv
Automatic scientific abstract text generation using RNNs

Anyone who has submitted scientific abstracts to conferences knows it tends to slip through the cracks and we tend to make it in just before the submission deadline. Wouldn't it be nice to have an abstract automatically written? In this project, I implement a LSTM-feed forward neural network structure for automatic character level text generation based on a corpus of abstracts downloaded through Cornell University's arxiv [API](https://arxiv.org/help/api). The html files were parsed with `BeautifulSoup` and then fed into the network for character level automatic text generation.

I spent a lot of time trying to design the network architecture, and with limited compute resources, I found it was taking a significant time to iterate between different architecture-hyperparameter combinations. For this reason, I implemented the same architecture used [here](https://github.com/spro/char-rnn.pytorch) for automatic text generation based on Shakespeare dialogs. All other code was written from scratch.
