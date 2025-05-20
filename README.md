# DA6401_A3
This repository contains all the code files for the assignment 3 of DA6401(Introduction to Deep Learning) 

# DA6401 Introduction to Deep Learning - Assignment 3

This repository contains all code files for Assignment 3 of the DA6401 (Introduction to Deep Learning) course.

## Contents

- [Task](#task)
- [Submission](#submission)
- [Dataset](#dataset)
- [Implementation Details](#implementation-details)
- [Tools and Libraries Used](#tools-and-libraries-used)
  - [Installation](#installation)


## Task

The task is to use recurrent neural networks to build a transliteration system.

## Submission

- **WandB Project:** (https://wandb.ai/ma23c047-indian-institute-of-technology-madras/DA6401_A3)
- **WandB Report:** (https://wandb.ai/ma23c047-indian-institute-of-technology-madras/DA6401_A3/reports/DA6401-Assignment-3--VmlldzoxMjU3MTMyOQ)

## Dataset

The dataset is a sample of the Dakshina dataset. It contains pairs of words in different languages for transliteration tasks.

## Implementation Details

This project implements an RNN-based sequence-to-sequence model for transliteration. The key components include:

- Data loading and preprocessing
- Encoder and decoder architectures using PyTorch
- Training, evaluation, and inference scripts
- Experiment tracking with WandB

## Tools and Libraries Used

- **Python 3.10.1**
- **PyTorch 2.0.0**
- **Pandas 1.5.3**
- **Weights & Biases (WandB)**
- **Jupyter Notebook** (for experimentation and reports)

### Installation

All required packages are listed in `requirements.txt`. Install them with:

```sh
pip install -r requirements.txt
