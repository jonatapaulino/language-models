# Language Models
Repository of pre-trained Language Models.
## French

### MultiFiT configuration (architecture 4 QRNN with 1550 hidden parameters by layer / tokenizer SentencePiece (15 000 tokens))
- notebook [lm3-french.ipynb](https://github.com/piegu/language-models/blob/master/lm3-french.ipynb) ([nbviewer of the notebook](https://nbviewer.jupyter.org/github/piegu/language-models/blob/master/lm3-french.ipynb)): code used to train a French Bidirectional LM on a 100 millions corpus extrated from Wikipedia by using the [MultiFiT](https://arxiv.org/pdf/1909.04761.pdf) configuration.
- link to download pre-trained parameters and vocabulary in [models]() soon...

### Architecture QRNN / tokenizer SentencePiece 
- notebook [lm2-french.ipynb](https://github.com/piegu/language-models/blob/master/lm2-french.ipynb) ([nbviewer of the notebook](https://nbviewer.jupyter.org/github/piegu/language-models/blob/master/lm2-french.ipynb)): code used to train a French Bidirectional LM on a 100 millions corpus extrated from Wikipedia
- link to download pre-trained parameters and vocabulary in [models](https://github.com/piegu/language-models/tree/master/models)
- notebook [lm2-french-classifier-amazon.ipynb](https://github.com/piegu/language-models/blob/master/lm2-french-classifier-amazon.ipynb) ([nbviewer of the notebook](https://nbviewer.jupyter.org/github/piegu/language-models/blob/master/lm2-french-classifier-amazon.ipynb)): code used to fine-tune a French Bidirectional LM and a Sentiment Classifier on "French Amazon Customer Reviews" dataset.

### Architecture AWD-LSTM / tokenizer spaCy 
- notebook [lm-french.ipynb](https://github.com/piegu/language-models/blob/master/lm-french.ipynb) ([nbviewer of the notebook](https://nbviewer.jupyter.org/github/piegu/language-models/blob/master/lm-french.ipynb)): code used to train a French Bidirectional LM on a 100 millions corpus extrated from Wikipedia
- link to download pre-trained parameters and vocabulary in [models](https://github.com/piegu/language-models/tree/master/models)
- notebook [lm-french-classifier-amazon.ipynb](https://github.com/piegu/language-models/blob/master/lm-french-classifier-amazon.ipynb) ([nbviewer of the notebook](https://nbviewer.jupyter.org/github/piegu/language-models/blob/master/lm-french-classifier-amazon.ipynb)): code used to fine-tune a French Bidirectional LM and a Sentiment Classifier on "French Amazon Customer Reviews" dataset.

