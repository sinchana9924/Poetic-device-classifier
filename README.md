# 📜 Poetic Device Classifier

## Overview

The Poetic Device Classifier is a machine learning pipeline built to identify poetic devices in text using natural language processing (NLP) and deep learning techniques. This project explores the intersection of AI and literature, focusing on how transformer-based models can detect figurative language, rhetorical techniques, and stylistic elements within poetic lines.

This tool can be extended for educational technology, literary analysis platforms, or as a creative tool to assist writers and poets.

---

## 🔍 What It Does

- Ingests poetic text from a structured dataset.
- Applies preprocessing steps to prepare data for modeling.
- Fine-tunes a transformer model (e.g., Mistral-7B or similar LLMs) on a poetic device classification task.
- Outputs predictions of poetic devices such as metaphor, simile, anaphora, alliteration, and more.
- Evaluates model performance using standard classification metrics.

---

## 📁 Files

- `Final_DATA641.ipynb`: Jupyter notebook containing the complete workflow – from data loading and preprocessing to training, prediction, and evaluation.
- `requirements.txt` *(to be added)*: Contains a list of required Python packages.

---

## ⚙️ Getting Started

### Prerequisites

Ensure you have Python 3.8+ and the following packages installed:

```bash
pip install torch transformers datasets bitsandbytes

```

---

## 📊 Interactive Report

Click the link below to explore the interactive Weights & Biases report with training metrics, model performance, and visual insights:

👉 [View Interactive Report on W&B](https://api.wandb.ai/links/sgarlave-university-of-maryland/70bodlo3)
