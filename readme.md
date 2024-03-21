# Disaster Detection on Twitter with BERT

This project aims to detect disasters in tweets using a BERT-based model. It utilizes a pre-trained BERT model and fine-tunes it on a dataset of tweets labeled as disaster or non-disaster.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Evaluation](#evaluation)
- [Contributing](#contributing)

## Introduction

With the increasing use of social media, platforms like Twitter provide valuable insights into real-time events, including disasters. This project focuses on automatically identifying tweets related to disasters, which can aid in disaster response and management.

## Installation

1. Clone the repository:

    ```bash
    https://github.com/sayan18012004/Twitter-Disaster-Detection.git
    ```

## Usage

1. Prepare your dataset: Ensure you have a dataset containing tweets labeled as disaster or non-disaster. Update the file paths in the code accordingly.

2. Train the model: Run the provided Python script to train the BERT-based model on your dataset.

3. Evaluate the model: Use the evaluation metrics such as confusion matrix and F1 score to assess the model's performance.

## Dataset

The dataset used in this project contains tweets collected from various sources and labeled as disaster or non-disaster. It's crucial to have a well-labeled dataset for training a reliable model.

## Model

The model architecture used in this project is based on BERT (Bidirectional Encoder Representations from Transformers), a state-of-the-art natural language processing model developed by Google. We utilize a pre-trained BERT model and fine-tune it on our disaster detection task.

## Evaluation

We evaluate the model's performance using metrics such as accuracy, precision, recall, and F1 score. Additionally, confusion matrices are used to visualize the model's predictions.

## Contributing

Contributions to this project are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or create a pull request.
