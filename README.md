#AI-Enabled Choreography


# Dance Generation and Visualization

This repository contains two main components: a generative model for dance sequences and a visualization tool for these sequences.

## Generative Model

The generative model is a Variational Autoencoder (VAE) with Long Short-Term Memory (LSTM). It is trained on dance sequences of length 64 and is designed to output a sequence of the same length. The model is implemented in PyTorch.

The training process includes the calculation of both the forecast loss and the KL divergence loss, which are characteristic of VAEs. The model is also tested on a separate test set, and the losses are reported.

The code for the generative model can be found in the `Generative-model.ipynb` file.

## Data Visualization

The data visualization tool is designed to visualize the input, output, and target sequences in 3D space. It uses matplotlib for plotting.

The visualization tool can handle sequences of varying lengths and can plot multiple sequences in a single figure. It also supports the visualization of skeleton lines if the joint labels are provided.

The code for data visualization can be found in the `Visualize-the-data.ipynb` file.
