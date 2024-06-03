# NN Learn from random value

## 1 Input(index) to 1 Output
This notebook is about seeing how neural network learn with only 1 input learns to fit a graph to some random datas. At first I tried to use a lot of datas, but even with a lot of epochs the loss is still very high.
So I tried using only 5 random datas and make them as simple as possible. And it works! The model can fit the graph to the datas.

## One Hot Encoding
Instead of passing only 1 input, I decided to convert index from 1 to DATA_AMOUNT into one hot encoding. For Example first index 0 turns into [1, 0, 0, ..., 0] or index 3 turns into [0, 0, 0, 1, ..., 0].
As a result the model is able to fit the graph into the datas even though the datas are a lot.
