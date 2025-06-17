

# MIT 6.S191 Lab 3: Fine-Tune an LLM, You Must!

Welcome to **Lab 3** of the [MIT Introduction to Deep Learning (6.S191)](http://introtodeeplearning.com) course!
In this lab, you'll gain hands-on experience with **fine-tuning large language models (LLMs)**—a core component of modern AI systems.

---

## 🧠 Lab Overview

This lab guides you through the **complete pipeline** for fine-tuning a **multi-billion parameter LLM** to generate responses in a specific style. You'll explore:

* Tokenization strategies for LLMs
* Prompt templates and dataset formatting
* Full fine-tuning workflow
* Automatic LLM-based evaluation using a "judge" model

This lab also introduces you to **modern tools** and **best practices** for evaluating and improving LLM outputs.

---

## 🔧 Tools & Models Used

| Component          | Description                                                                   |
| ------------------ | ----------------------------------------------------------------------------- |
| 🔤 **Base Model**  | [Gemma 2B](https://ai.google.dev/gemma) — an open-weight LLM by Google        |
| ⚖️ **Judge Model** | [LFM-40B](https://liquid.ai/) — a 40B-parameter evaluation model by Liquid AI |
| 📊 **Evaluation**  | [Opik](https://www.comet.com/) by Comet ML — a framework for LLM evaluation   |

---

## 🚀 What You Will Do

* Load and tokenize prompts and responses
* Fine-tune a pre-trained LLM on a style-specific dataset
* Use **Comet ML's Opik** to automatically evaluate your model's outputs
* Interpret evaluation metrics to understand model performance

---

## 📁 Contents

| File/Notebook          | Description                                         |
| ---------------------- | --------------------------------------------------- |
| `LLM_FineTuning.ipynb` | Main notebook for model fine-tuning and evaluation  |
| `data/`                | Contains training/evaluation prompts                |
| `utils.py`             | Helper functions for tokenization, evaluation, etc. |
| `README.md`            | This file                                           |

---

## 📦 Requirements

* Python 3.8+
* HuggingFace Transformers
* Accelerate, PEFT (for parameter-efficient fine-tuning)
* Opik (by Comet ML)
* Optional: Google Colab or a GPU runtime (recommended)

You can install dependencies via:

```bash
pip install -r requirements.txt
```

Or install manually inside Colab/notebook cells as needed.

---

## 🧪 Getting Started

1. Clone the repo or open the notebook in Google Colab.
2. Set up the required API keys (if applicable).
3. Follow the instructions in the notebook to fine-tune and evaluate.
4. Adjust dataset templates and model configs to experiment!

---

## 🎯 Learning Objectives

By completing this lab, you will:

* Understand how LLMs process and tokenize text
* Learn how to structure prompt-response datasets for training
* Fine-tune a modern LLM with minimal compute
* Evaluate and compare model outputs using an automated judge
* Gain practical experience with open-source LLMs

---

## 📜 License

This project is part of MIT 6.S191: Introduction to Deep Learning.
It is licensed under the **MIT License**.

> © MIT Introduction to Deep Learning
> [http://introtodeeplearning.com](http://introtodeeplearning.com)



