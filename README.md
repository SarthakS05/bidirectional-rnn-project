# TensorFlow Bidirectional RNN

A bidirectional LSTM classifier for MNIST that reads each 28-pixel image row as a sequence.

## Run

Use Python 3.10 with the pinned dependencies:

```bash
python -m pip install -r requirements.txt
python bidirectional_rnn.py
```

Keras downloads MNIST on first run. The script trains for 1,000 steps and reports batch loss and accuracy during training.

## Attribution

The notebook credits Aymeric Damien and the [TensorFlow-Examples project](https://github.com/aymericdamien/TensorFlow-Examples/).