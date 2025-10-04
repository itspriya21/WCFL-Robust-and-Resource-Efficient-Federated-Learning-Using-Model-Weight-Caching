# fedhybrid-CIFAR

# FedHybrid CIFAR-10 Notebook

This repository contains an implementation of **FedHybrid** (a hybrid federated learning method that mixes FedAvg with Newton-type client updates) on the **CIFAR-10 dataset**.

## Contents
- `fed_hybrid_final.ipynb` — Jupyter Notebook implementing FedAvg and FedHybrid.
- `README.md` — Documentation.

## Requirements
- Python 3.9+
- PyTorch
- torchvision
- numpy

## How to Run
1. Open the notebook in Jupyter or Google Colab.
2. Install dependencies:
   ```bash
   pip install torch torchvision numpy


##Configure training parameters in the notebook:

num_rounds — Total federated training rounds (e.g., 50)

local_epochs — Number of epochs per client per round (e.g., 2)

batch_size — Mini-batch size (e.g., 64)

device — 'cuda' for GPU, 'cpu' otherwise

Run each cell sequentially to:

Load CIFAR-10 dataset

Initialize models and clients

Run FedAvg and FedHybrid training

Observe training accuracy and loss over rounds
