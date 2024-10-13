# Graph Neural Network for Node Classification on Cora Dataset

## Overview
This project implements a Graph Neural Network (GNN) using PyTorch Geometric (PyG) to classify nodes in the Cora dataset, which is a citation network where each node represents a scientific paper, and edges represent citation relationships. The model aims to predict the research topic of each paper, categorized into seven distinct classes.

## Dataset
The Cora dataset contains 2,708 scientific papers classified into one of seven categories. Each paper is represented as a node with features based on the words it contains, and edges represent citation relationships between the papers.

## Requirements
To run this project, you need to install the following libraries:
- `torch`
- `torch_geometric`
- `networkx`
- `matplotlib`

You can install these packages using pip:
```bash
pip install torch torch_geometric networkx matplotlib
