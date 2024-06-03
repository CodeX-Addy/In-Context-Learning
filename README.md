# In-Context Learning with FLAN-T5 

This project demonstrates in-context learning techniques (zero-shot, one-shot, few-shot learning) using the FLAN-T5 model within the AWS SageMaker environment. In-context learning enables the model to perform tasks with minimal to no task-specific training examples.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [In-context Learning Techniques](#in-context-learning-techniques)
  - [Zero-shot Learning](#zero-shot-learning)
  - [One-shot Learning](#one-shot-learning)
  - [Few-shot Learning](#few-shot-learning)
- [Usage](#usage)
- [License](#license)

## Introduction

In-context learning with the FLAN-T5 model allows for flexible and efficient learning by providing the model with various examples directly at inference time. This project explores different in-context learning approaches using AWS SageMaker.

## Project Structure

- `data/`: Directory containing example datasets.
- `notebooks/`: Jupyter notebooks for in-context learning demonstrations.
- `src/`: Source code for model inference.
- `README.md`: Project documentation.
- `requirements.txt`: List of dependencies required for the project.

## Prerequisites

- AWS Account with SageMaker permissions
- Python 3.7+
- AWS CLI configured with your credentials

## Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/CodeX-Addy/In-Context-Learning.git
    cd In-Context-Learning
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up AWS SageMaker:**
    - Launch a SageMaker notebook instance.
    - Upload the project files to the instance.

## In-context Learning Techniques

### Zero-shot Learning

Zero-shot learning involves providing the model with a task description without any specific examples.

### One-shot Learning

One-shot learning involves providing the model with one example to learn the task.

### Few-shot Learning

Few-shot learning involves providing the model with a few examples to learn the task.

## Usage

1. **Run the Jupyter notebook:**
    - Open `notebooks/flan_t5_in_context_learning.ipynb` in SageMaker.
    - Follow the instructions in the notebook to perform in-context learning.

2. **Model Inference:**
    - Use `src/inference.py` to run inference on new data.

    ```bash
    python src/inference.py --mode zero-shot --input "Your input text here"
    ```


## License

This project is licensed under the MIT License.


