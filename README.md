# SelfScheduled Neural Clustering Architecture
Neural Clustering Architecture for Tabular Data (Customer Segmentation/Persona Creation)
This repo contains the official PyTorch implementation of the neural architecture proposed in [____]. This architecture is designed for clustering tabular data, leveraging autoencoders and a routing network. This work expands on existing work that follows a Mixture of Experts approach for clustering images and text. 

One key contribution from this work is the novel training schedule, which dynamically adjusts its own hyperparameters throughout training in a self-learning loop. This approach prevents model collapse and eliminates the need for manual hyperparameter tuning, making the training process more stable and efficient. This is specially valauable for practitioners, since clustering tasks contain no labels for efficient parameter tuning. 

## 1.1: How to use on your own dataset
The file "SelfScheduled_Neural_Clustering.ipynb" contains an example for running the network and includes code for you to run it on your own dataset.
This file is a Google Colab Notebook, so all the code is already written for you:

- 1. Click on the "Example" folder
- 2. Click "SelfScheduled_Neural_Clustering.ipynb" 
- 3. Click "Open in Colab" at the top
- 4. Follow the instructions in the notebook
