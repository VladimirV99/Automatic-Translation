# Automatic-Translation

Automatic language translation using a sequence-to-sequence LSTM model

## Required packges

- python
- pip
- graphviz

## Required libraries

- notebook
- numpy
- pandas
- tensorflow
- pydot
- nltk
- scikit-learn
- matplotlib

If you have conda installed, you can create an evironment with all required packages installed by running the following commands
```bash
conda env create -f environment.yml
conda activate translation
```

## Datasets

English word list: https://github.com/dwyl/english-words

French word list: http://www.lexique.org/

English-to-French translation datasets: 
- http://www.manythings.org/anki/
- https://www.tensorflow.org/datasets/catalog/wmt14_translate

## References

- https://arxiv.org/pdf/1409.3215.pdf
- https://google.github.io/seq2seq/
- https://keras.io/examples/nlp/lstm_seq2seq/
