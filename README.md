# wgg_research

Research of nlp models with word embeddings

## Setting up the environment 

Run `pip install -r requirements.txt`

## Experiments

1\. [This notebook](bert.ipynb) demonstrates an example of usage Bert model for embeddings getting.  [Bert](https://huggingface.co/docs/transformers/model_doc/bert) is a bidirectional transformer pretrained using a combination of masked language modeling objective and next sentence prediction on a large corpus comprising the Toronto Book Corpus and Wikipedia.

2\. [This notebook](word2vec.ipynb) shows an example with word2vec embeddings. The [word2vec](https://radimrehurek.com/gensim/models/word2vec.html) algorithms include skip-gram and CBOW models, using either hierarchical softmax or negative sampling. In this example, a pre-trained 'glove-twitter-25' model is used.

3\. [In this notebook](fasttext.ipynb) we are trying to get embeddings of the fasttext model. [FastText](https://radimrehurek.com/gensim/auto_examples/tutorials/run_fasttext.html) can obtain vectors even for out-of-vocabulary (OOV) words, by summing up vectors for its component char-ngrams. In this example, a pre-trained "crime-and-punishment.bin" model is used.

