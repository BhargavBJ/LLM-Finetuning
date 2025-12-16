## LLM-Finetuning

This repository presents example workflows for parameter-efficient fine-tuning (LoRA) of **Gemma** and **Qwen** large language models.

## Overview

Large Language Models (LLMs) are computationally expensive to fine-tune using full-parameter updates. This repository demonstrates how **Low-Rank Adaptation (LoRA)** can be used to efficiently fine-tune Gemma and Qwen models while significantly reducing memory and compute requirements. The examples are designed to be easy to understand and adaptable for research, experimentation, and downstream applications.

## Features

* LoRA-based fine-tuning implementations for:

  * Gemma models
  * Qwen models
* Parameter-efficient training with reduced memory footprint
* Jupyter Notebook–based workflows for clarity and reproducibility
* Configurable LoRA parameters for experimentation
* Easily extensible for custom datasets and tasks

## Requirements

* Python 3.9+
* PyTorch
* Hugging Face `transformers`
* `peft` (for LoRA)
* `datasets`
* CUDA-enabled GPU (recommended)

## Customization

Download the notebook and the workflows can be extended or modified to:

* Incorporate custom datasets
* Tune LoRA hyperparameters such as rank, alpha, and target modules
* Adapt models for tasks including instruction tuning, domain adaptation, and text classification

## Use Cases

* Research on parameter-efficient fine-tuning methods
* Rapid prototyping of domain-specific LLMs
* Educational demonstrations of LoRA-based training
* Fine-tuning large models under limited computational resources

## Disclaimer

The models and examples provided in this repository are intended for research and educational purposes only. Users are responsible for ensuring compliance with the licenses of the respective base models, including Gemma and Qwen.

## Acknowledgements

* Hugging Face Transformers and PEFT libraries
* Google Research (Gemma)
* Alibaba Cloud (Qwen)
