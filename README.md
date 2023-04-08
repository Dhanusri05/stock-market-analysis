# Stock Market analysis

## Overview
* A analysis of the stock market and making a predictions using LSTM (Long short-term memory).


## What is LSTM (Long short-term memory)?
Long Short Term Memory networks – usually just called “LSTMs” – are a special kind of RNN, capable of learning long-term dependencies. They were introduced by Hochreiter & Schmidhuber (1997), and were refined and popularized by many people in following work. They work tremendously well on a large variety of problems, and are now widely used.

LSTMs are explicitly designed to avoid the long-term dependency problem. Remembering information for long periods of time is practically their default behavior, not something they struggle to learn!

All recurrent neural networks have the form of a chain of repeating modules of neural network. In standard RNNs, this repeating module will have a very simple structure, such as a single tanh layer.


## For more informations about LSTM (Long short-term memory):
  * https://colah.github.io/posts/2015-08-Understanding-LSTMs/
  
  * https://machinelearningmastery.com/gentle-introduction-long-short-term-memory-networks-experts/
  
  * https://www.analyticsvidhya.com/blog/2021/03/introduction-to-long-short-term-memory-lstm/
  

### Run locally
Install dependencies ([virtual-environment](https://en.whiteboxml.com/blog/the-definitive-guide-to-python-virtual-environments-with-conda) is recommended.)

```python
pip install -r requirements.txt
```

