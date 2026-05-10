# GPT-2 Language Model

A replication and exploration of OpenAI's GPT-2, based on the research paper [**"Language Models are Unsupervised Multitask Learners"**](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) by Radford et al. (2019).

## What I Did

- Loaded and ran inference with pretrained GPT-2 model weights (up to 1.5B parameters)
- Explored text generation capabilities across different model sizes (124M, 355M, 774M, 1.5B parameters)
- Investigated model biases and factual accuracy limitations as described in the original model card
- Documented use cases including writing assistance, creative text generation, and code autocompletion

## Research Paper

This project is based on:

> Radford, A., Wu, J., Child, R., Luan, D., Amodei, D., & Sutskever, I. (2019).
> **Language Models are Unsupervised Multitask Learners.**
> OpenAI.

- **Paper**: [Read here](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
- **Blog post**: [OpenAI announcement](https://openai.com/blog/better-language-models/)

## Training Data

GPT-2 was trained on **WebText**, a dataset of 45 million outbound links from Reddit, filtered for quality. The data cuts off at end of 2017.

## Caveats

- GPT-2 does not distinguish fact from fiction; outputs should not be treated as factually reliable
- The model reflects biases present in its internet-scale training data
- Always label synthetic text as such before sharing it widely
