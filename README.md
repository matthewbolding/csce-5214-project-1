# CSCE 5214 Project 1

## About

This Jupyter Notebook creates a simple feed forward neural network to determine whether a transaction is fraudulent. This project is a demonstration of the knowledge of the pieces that make a neural network and its supporting infrastructure, so the model does not perform well at determining a transaction's fraudulent status.

## Getting Started

To get started, you must have the program `uv` installed. After cloning this repository, run `uv sync`, which will install all the needed libraries to a local virtual environment.

You must also download the data and place it in the correct local folder. Run these commands.

bash
```
$ curl -L -o archive.zip https://www.kaggle.com/api/v1/datasets/download/teamincribo/credit-card-fraud
$ mkdir data
$ unzip -d data archive.zip
```


Developed by Matthew Bolding for CSCE 5214, Spring 2025.