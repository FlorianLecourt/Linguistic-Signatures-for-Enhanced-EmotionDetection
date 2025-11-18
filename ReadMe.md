# Linguistic Signatures for Enhanced Emotion Detection

[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.7.0-ee4c2c.svg)](https://pytorch.org/)

//Correct after acceptance//
[![Paper](https://img.shields.io/badge/arXiv-Paper-brightgreen.svg)](TODO_ADD_LINK)

## 📋 Table of Contents
- [Description](#-description)
- [Quick Start](#-quick-start)  
- [References](#-references)
- [Citation](#-citation)
- [Acknowledgments](#acknowledgments)

## 📖 Description

This repository provides trained models and linguistic signatures for fine-grained emotion detection on the GoEmotions dataset.

### Repository Structure

- **`Models/`** - RoBERTa fine-tuned models 
  - Per-seed folders with model weights, metrics, and predictions
  - Training/evaluation notebooks
  - Llama3.2 0-shot & 1-shot prompts + responses
  - Summary visualizations (loss curves, boxplots)

- **`Reproduction/`** - Reproduced SOTA baseline results

- **`Signatures/`** - Linguistic signatures by dataset/emotion
  - **`PieCharts/`** - Pie chart visualizations
  - **`Histograms/`** - Bar chart representations

- **`Emotion Comparisons/`** - 30 emotion categories with GI Features (General Inquirer lexicon features)


## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/linguistic-signatures-emotion.git
cd linguistic-signatures-emotion

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt
```

### List of dependencies

* Python 3.11
    + datasets 3.6.0
    + matplotlib 3.10.3
    + numpy 2.2.5
    + pandas 2.2.3
    + pillow 11.2.1
    + scikit-learn 1.6.1
    + seaborn 0.13.2
    + torch 2.7.0
    + tqdm 4.67.1
    + transformers 4.51.3
    + ollama 0.6.1

## 📖 References

- [GoEmotions Dataset](https://research.google/blog/goemotions-a-dataset-for-fine-grained-emotion-classification/)
- [ChatGPT: Jack of all trades, master of none](https://arxiv.org/abs/2302.10724)

## 📖 Citation

If you use this work, please cite:

//Correct after acceptance//
```bibtex
@article{your_name2024linguistic,
  title={Linguistic Signatures for Enhanced Emotion Detection},
  author={Your Name and Colleagues},
  year={2025}
}
```

## Acknowledgments

This research was supported by the European Regional Development Fund (FEDER) through the IA-EMOTION project.

*Linguistic signatures for enhanced emotion detection*