# Generative AI Text Generation Assignment

## Project Overview

This project explores the fundamentals of **Generative Artificial Intelligence (AI)** with a focus on text generation. It demonstrates how machine learning models can learn patterns in text data and generate human-like content.

The implementation includes:

* Understanding of Generative AI concepts
* Overview of Generative Pre-trained Transformers (GPTs)
* A hands-on text generation model built using Python and TensorFlow
* A simple content creation application

## Objectives

* Understand the architecture of GPT models
* Implement a basic text generation model
* Train the model on real-world text data
* Demonstrate a practical application of generative AI
* Analyze ethical implications of AI-generated content

## Dataset

### Source

This project uses a publicly available dataset from **Project Gutenberg**.

Example text used:

* *Alice’s Adventures in Wonderland* (Public Domain)

### Dataset Link

https://www.gutenberg.org/files/11/11-0.txt

### Why This Dataset?

* Public domain and freely accessible
* Clean and well-structured text
* Suitable size for training in Google Colab

## Model Architecture

Although GPT models are based on the **Transformer architecture**, this project implements a simplified **LSTM-based neural network** to demonstrate text generation concepts.

### Key Components:

* Character-level tokenization
* One-hot encoding
* LSTM (Long Short-Term Memory) layer
* Dense output layer with softmax activation

### Why LSTM Instead of GPT?

* Easier to implement for beginners
* Requires less computational power
* Demonstrates sequence learning effectively

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Google Colab

## Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/kadiwala1234/Assignment-13-Generative-AI-Essentials.git
cd Assignment-13-Generative-AI-Essentials
```
### 2. Install Dependencies

```bash
pip install tensorflow numpy
```

### 3. Run Notebook

Open the notebook in **Google Colab** or Jupyter Notebook:

```bash
jupyter notebook
```

## How It Works

### Step 1: Data Preprocessing

* Load raw text
* Convert text into character sequences
* Create input-output pairs

### Step 2: Model Training

* Train LSTM model on sequences
* Optimize using categorical cross-entropy loss

### Step 3: Text Generation

* Provide a seed sentence
* Model predicts next character
* Repeats to generate full text

## Example Output

**Input Seed:**

```
Alice was beginning to
```

**Generated Text:**

```
Alice was beginning to feel very curious about the strange rabbit...
```

## Results & Observations

* The model learns basic grammar and sentence flow
* Longer training improves coherence
* Small datasets limit creativity and accuracy
* Character-level models generate more flexible but less structured text

## Application Demo

### AI Story Generator

A simple application where:

* User inputs a starting sentence
* Model generates story continuation

#### Use Cases:

* Creative writing assistance
* Story generation
* Educational demonstrations

## Ethical Considerations

### Issues:

* Bias in training data
* Risk of plagiarism
* Misinformation generation
* Lack of interpretability

### Solutions:

* Use high-quality datasets
* Apply content filtering
* Ensure transparency in AI usage
* Incorporate human oversight

## Report

The detailed report includes:

* Introduction to Generative AI
* GPT architecture explanation
* Implementation methodology
* Results and analysis
* Ethical considerations

## Future Improvements

* Implement Transformer-based model (closer to GPT)
* Use larger datasets (e.g., The Pile)
* Fine-tune pretrained models
* Improve text coherence with advanced sampling methods

## License

This project is for academic purposes only. Dataset sourced from Project Gutenberg (public domain).
