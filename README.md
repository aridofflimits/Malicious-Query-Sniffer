# Malicious Query Sniffer

## Overview

The goal of this project is to develop models capable of accurately detecting malicious web queries that could indicate potential cyber attacks such as SQL injection, cross-site scripting (XSS), local file inclusion (LFI), and other types of exploits. 

A dataset of benign and malicious queries is used to train and evaluate different machine learning and deep learning classification algorithms. The models aim to learn patterns and semantics that distinguish between innocuous and harmful query strings.

Specifically, the following machine learning and deep learning techniques are implemented:

- Traditional machine learning algorithms including decision trees, ensemble methods, logistic regression, etc. These are based on extracting engineered features from the raw query text.

- Deep neural networks like LSTMs and convolutional models. These have the ability to learn hierarchical representations and capture complex patterns directly from the input query strings.

Each model is rigorously evaluated using cross-validation to score their performance on classification metrics such as accuracy, precision, recall and F1. This process identifies the most effective technique for this task.

By developing models with high detection capabilities, the goal is to automate the identification of malicious queries aimed at exploiting vulnerabilities. This could help security professionals more quickly analyze and respond to potential attack vectors.

Overall, the project seeks to determine whether traditional machine learning or more modern deep learning is best suited for this query classification problem. Both approaches are explored to uncover the most powerful approach.
