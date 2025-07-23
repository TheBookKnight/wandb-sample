# Sample Script: Weights & Biases Integration

This directory contains a simple Python script demonstrating how to track machine learning experiments using [Weights & Biases (wandb)](https://wandb.ai/).

## Overview

- The script (`sample.py`) simulates training a model and logs metrics (accuracy and loss) to wandb.
- Hyperparameters and metadata are tracked for reproducibility.
- Results are automatically uploaded and viewable in your wandb dashboard.

## Usage

1. **Install dependencies**  
   Make sure you have Python 3.13+ and install required packages:
   ```sh
   pip install wandb