# BertModel_Classification

A language model is a probability distribution over sequences of words. Given such a sequence of length m, a language model assigns a probability P to the whole sequence. Language models generate probabilities by training on text corpora in one or many languages.

Here, I have coded them both in .py and .ipynb format for better understanding of both formats. 

### Bert model:
Bidirectional Encoder Representations from Transformers is a transformer-based machine learning technique for natural language processing pre-training developed by Google.


The techniques we use:

**Setup:** import packages, read data, Preprocessing, Partitioning.

**Bag-of-Words:** Feature Engineering & Feature Selection & Machine Learning with scikit-learn, Testing & Evaluation, Explainability with lime.

**Word Embedding:** Fitting a Word2Vec with gensim, Feature Engineering, Hybrid model with LSTM layer and Deep Learning with tensorflow/keras, Testing & Evaluation.

**Language Models:** Feature Engineering with transformers, Fine tunning a pre-trained BERT with transformers and tensorflow/keras, Testing & Evaluation.

### The dataset:

<img src="https://user-images.githubusercontent.com/84439960/186622912-396d4a1b-ed6b-488f-950f-7b1a6c4048be.jpg" width="400" height="400" />


I love superheros ! especially I am a big Marvel fan. So I want to do something interesting for language models and I picked up  the superhero dataset from kaggle. You can do many things with this dataset! But here I am trying to use it for text classification.
I want to see based on the history description of superheros, if I can find who their creators are! 
