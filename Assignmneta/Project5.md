# Implementing an LLM Text Generator on the Persian Wikipedia Dataset

## Introduction

In this exercise, you will develop a text generator using a large language model (LLM) on the Persian Wikipedia dataset. The goal is to implement the model from scratch, without utilizing pre-trained networks or fine-tuning existing models.

## Steps to Complete the Exercise

### 1. Dataset Creation
- **Objective**: Create a text generation dataset from the Persian Wikipedia using the `torch.utils.data.dataset` class.
- **Instructions**:
  - Extract and preprocess text data from the Persian Wikipedia.
  - Tokenize the text data and create sequences suitable for training a text generation model.
  - Implement a custom dataset class in PyTorch that handles data loading and batching.

### 2. Model Implementation
- **Objective**: Implement your neural network for text generation, focusing on designing and coding the model’s architecture.
- **Instructions**:
  - Design the architecture of your LLM, including the embedding layer, recurrent or transformer-based layers, and the output layer.
  - Implement the model in PyTorch, ensuring that it is capable of handling the tokenized text sequences created in the previous step.

### 3. Training the Model
- **Objective**: Train your network on the created dataset, ensuring proper data handling, batching, and training loops.
- **Instructions**:
  - Set up the training loop, including forward and backward passes, loss computation, and parameter updates.
  - Use appropriate techniques such as gradient clipping and learning rate scheduling to stabilize training.
  - Monitor the training process through loss curves and other relevant metrics.

### 4. Model Evaluation
- **Objective**: Evaluate your model using Perplexity, ROUGE, and other relevant evaluation metrics.
- **Instructions**:
  - Calculate Perplexity to measure the model’s ability to predict the next word in a sequence.
  - Use ROUGE scores to evaluate the quality of the generated text against reference outputs.
  - Provide a detailed explanation of the challenges encountered during text generation, focusing on issues like model convergence, overfitting, and output coherence.

## Extra Bonus

- **Pre-training and Fine-tuning**:
  - **Objective**: Apply pre-training to your network for additional points and fine-tune it on the Persian Wikipedia dataset.
  - **Instructions**:
    - Choose a suitable pre-training task (e.g., language modeling, masked language modeling) and implement it.
    - Fine-tune the pre-trained model on the Persian Wikipedia dataset.
    - Provide a detailed explanation of the pre-training task, including the rationale behind its choice and how it improves the model’s performance on the text generation task.

## Conclusion

Upon completing this exercise, you will have developed a deep understanding of how to build, train, and evaluate a large language model for text generation. By working through the steps from dataset creation to model evaluation, and potentially enhancing the model with pre-training, you will gain practical experience in handling complex natural language processing tasks in PyTorch.
