# Integer Sequence Learning

Solution for [*"Integer Sequence Learning"* problem at Kaggle:](https://www.kaggle.com/c/integer-sequence-learning) with LSTM and Keras.

## How to run:

- Place `train.csv`, `test.csv` in project dir
- **encode-seqs**
- **train**
- **create-subm**

## Approach

Integers are treated as words. Frequency threshold is used to reduce the dictionary size (~50% cases can be constructed of integers appearing in 10 or more sequences).

Hence with the threshold of 10, leaderboard score can be expected to be roughly 1/2 of achieved `val_acc` metric.
