# HiddenLayerLens 🧠🔍

![HiddenLayerLens](https://mybubblpublic.s3.ap-south-1.amazonaws.com/HiddenLayerLens.jpeg)

## Description
HiddenLayerLens is a deep dive into the internal representations of open-source large language models (LLMs). This repository contains the **first** direct comparison of hidden layer activations between:

- **[NousResearch/Hermes-3-Llama-3.2-3B](https://huggingface.co/NousResearch/Hermes-3-Llama-3.2-3B)**
- **[meta-llama/Llama-3.2-3B](https://huggingface.co/meta-llama/Llama-3.2-3B)**

By analyzing hidden states layer-by-layer, we aim to uncover how these models encode and transform information across their architectures. This can provide valuable insights into representation learning, transferability, and architectural modifications.

## Features
✅ **Layer-wise Comparison** – Cosine similarity, CKA, and L2 distance between hidden representations.

✅ **Visualization** – Heatmaps and projections of hidden state differences.

✅ **Insights** – Understanding divergence points in model architectures and fine-tuning effects.

✅ **Colab Notebook** – Run your own comparisons with minimal setup!

## Usage
You can explore the analysis using our **Google Colab notebook** (link coming soon!). The repository provides scripts to extract, compare, and visualize hidden states from the selected models.

## Credit
This work is inspired by ongoing discussions in the AI research community. Special thanks to [@XCossale](https://x.com/XCossale/status/1886742282675884102) & [@Tokenblender](https://x.com/tokenbender) for their insightful tweet that sparked this project.

---

🚀 **Contributions & Feedback**
We welcome contributions! If you find issues or have suggestions, feel free to open a discussion or pull request.

📢 Stay tuned for updates and deeper analyses!

