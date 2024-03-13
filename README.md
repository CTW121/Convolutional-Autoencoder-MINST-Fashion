# Convolutional Autoencoder (CAE)
- CAE is implemented to learn the underlying distribution of a dataset which can help in:
    - detecting out of distribution data points,
    - learning relevant features of the data,
    - performing classification when only very few labels are present.
- PyTorch is utilized.
- Variational Autoencoder is implemented.
- MINST Fashion dataset is used.

## Goal
- Detect out of distribution data.
- Give a low dimensional description of the dataset in terms of the five modes of the distribution.
- To classify the remaining data points into the five classes.