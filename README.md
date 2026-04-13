# Mini Language Model using PyTorch

## Overview

This project implements a basic character-level language model using PyTorch. The model is trained on the WikiText dataset and is capable of generating text sequences based on learned character patterns. The purpose of this project is to understand the fundamental concepts behind large language models, including tokenization, sequence modeling, and probabilistic text generation.

---

## Features

* Character-level tokenization
* Text generation using a neural network
* Training on real-world dataset (WikiText)
* Simple and beginner-friendly implementation
* Demonstrates core concepts of language modeling

---

## Tech Stack

* Python
* PyTorch
* HuggingFace Datasets

---

## Project Structure

```
mini-llm-project/
│── mini_llm.ipynb
│── README.md
```

---

## How It Works

1. The dataset is loaded using the HuggingFace datasets library.
2. Text data is preprocessed and converted into character-level tokens.
3. Each character is mapped to a numerical index (encoding).
4. A neural network model is trained to predict the next character in a sequence.
5. The trained model generates new text by sampling from learned probability distributions.

---

## Installation

### 1. Clone the repository

```
git clone https://github.com/your-username/mini-llm-project.git
cd mini-llm-project
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

---

## Usage

### Run the notebook

Open the notebook file and run all cells:

```
mini_llm.ipynb
```

### Train the model

The model is trained using a simple training loop defined in the notebook. Training progress is displayed using loss values.

### Generate text

After training, the model can generate text sequences based on a starting input.

Example:

```
Input: Artificial intelligence
Output: Artificial intelligence and the the of the...
```

---

## Results

The model is able to learn basic character patterns and generate text that resembles English structure. However, due to its simplicity and limited training, the output may not always be semantically meaningful.

---

## Limitations

* Uses a simple bigram model, not a transformer-based architecture
* Limited understanding of context and semantics
* Output quality depends heavily on training duration and dataset size

---

## Future Improvements

* Implement transformer-based architecture (GPT-style model)
* Use word-level or subword tokenization
* Increase training data and training iterations
* Add evaluation metrics and visualization
* Deploy as a web-based application

---

## Learning Outcomes

* Understanding of tokenization and encoding techniques
* Basics of language modeling and sequence prediction
* Implementation of training loops in PyTorch
* Fundamentals of text generation using neural networks

---

## Author

Shami kumar
