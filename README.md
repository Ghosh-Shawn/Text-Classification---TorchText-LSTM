# Text Classification in Pytorch
* The notebook shows how to use `Torchtext` to create a vocabulary, create a Dataset for the text data and an Iterator to pass the data to a model for training.
* Torchtext has predefined methods to load CSV, TSV and JSON data. In this notebook there is a seperate class (inheriting `torchtext.data.Dataset`) which can be used to load data from a `Pandas DataFrame`. The class is a modification of the work of [lextoumbourou](https://gist.github.com/lextoumbourou/8f90313cbc3598ffbabeeaa1741a11c8) 


####  The Data used here is from a Kaggle competition Dataset : [Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started) 


## Preprocessing using Torchtext
* The texts are padded 
* [Glove](https://nlp.stanford.edu/projects/glove/) pre-trained vectors are used (6 billion tokens - 200 dimension). 

## LSTM model
