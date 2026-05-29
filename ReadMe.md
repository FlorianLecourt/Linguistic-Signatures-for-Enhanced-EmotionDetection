# Linguistic Signatures for Enhanced Emotion Detection

[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.7.0-ee4c2c.svg)](https://pytorch.org/)
[![Paper](https://img.shields.io/badge/arXiv-2603.20222-b31b1b.svg)](https://arxiv.org/pdf/2603.20222)

## 📋 Table of Contents
- [Description](#-description)
- [Quick Start](#-quick-start)  
- [References](#-references)
- [Citation](#-citation)
- [Acknowledgments](#acknowledgments)

## 📖 Description

This repository provides trained models for fine-grained emotion detection on the GoEmotions dataset, plus linguistic signatures for emotion labels from 13 English datasets.

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

- **`Emotion Comparison/`** - 30 emotion categories with GI Features (General Inquirer lexicon features)


## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/FlorianLecourt/Linguistic-Signatures-for-Enhanced-EmotionDetection.git
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
    + datasets 4.4.1
    + matplotlib 3.10.7
    + numpy 2.3.5
    + pandas 2.3.3
    + pillow 12.0.0
    + scikit-learn 1.7.2
    + seaborn 0.13.2
    + torch 2.9.1
    + tqdm 4.67.1
    + transformers 4.57.1
    + ollama 0.6.1

## 📖 References

- [GoEmotions Dataset](https://research.google/blog/goemotions-a-dataset-for-fine-grained-emotion-classification/), used for training and evaluation.
- [ChatGPT: Jack of all trades, master of none](https://arxiv.org/abs/2302.10724), reproduced baseline for emotion detection.
- The [NLP-resources](https://github.com/vishwa94sai/NLP-Resources) repository, made available by [Vishwa et al.](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9679993), used for preprocessing.
- [General Inquirer lexicon](https://inquirer.sites.fas.harvard.edu/homecat.htm), used for linguistic signature analysis.

## 📖 Citation

If you use this work, please cite:

```bibtex
@article{lecourt2026linguistic,
  title={Linguistic Signatures for Enhanced Emotion Detection},
  author={Lecourt, Florian and Croitoru, Madalina and Todorov, Konstantin},
  journal={arXiv preprint arXiv:2603.20222},
  year={2026}
}
```

## Acknowledgments

This research was supported by the European Regional Development Fund (FEDER) through the IA-EMOTION project.
