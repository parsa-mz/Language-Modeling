## Language Modeling on Penn Treebank

## Introduction

The primary objective of this project is to design and train a language model on the Penn Treebank dataset. The Penn Treebank is a corpus of approximately 1 million tokens, which might seem extensive but is relatively small for language models. The goal is to predict the next token in a sequence based on the preceding N tokens. This project is a venture into the realm of unsupervised learning, and participants are encouraged to experiment with various architectures and techniques, including RNN, LSTM, GRU, attention mechanisms, different tokenizers, pretrained embeddings, hyperparameter tuning, regularization, and dropout.

## Requirements

This project has been implemented using [Python 3.10](https://www.python.org/downloads). 

To set up your environment and install the necessary dependencies:

```bash
    # create a virtual environment
    py -m venv env
    # windows only
    env\Scripts\activate
    # linux or mac
    source env/bin/activate
    
    # install requirements
    pip install -r requirements.txt
```

Additionally, you'll need to fetch the Penn Treebank dataset using the `datasets` library from huggingface. Instructions on how to load and preprocess the data are provided in the project description.

## Running the Code

The code is primarily written in a Jupyter notebook format, which allows for iterative experimentation and analysis. This format is also compatible with Google Colab for those who prefer cloud-based execution with GPU support.

## Project Structure

```bash
    .
    ├── README.md
    ├── requirements.txt
    └── Language_Modeling.ipynb
```

The `data` directory hosts the Penn Treebank dataset split into training, validation, and test sets. The Jupyter `notebook` contains the code, including model definitions, data preprocessing, training loops, and evaluation metrics.

## Model

Participants are encouraged to experiment with a plethora of model architectures and techniques. This includes classical RNN structures, LSTMs, GRUs, attention mechanisms, and more. Additionally, experimenting with pretrained embeddings such as word2vec or GloVe can be beneficial, though using pretrained models like BERT or GPT-3 is not allowed.


## Authors

Parsa Mazaheri, Dec 2022