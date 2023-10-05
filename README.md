# 🧠 Question-Answering Model for Schizophrenia Symptoms

![QA Header](https://unsplash.com/photos/hluOJZjLVXc)

> **A deep dive into the world of Schizophrenia through the lens of Machine Learning.** 

This repository is dedicated to understanding Schizophrenia symptoms and their impact on daily life, leveraging vast data from mental health forums and advanced ML models.

[![PapersWithCode](https://img.shields.io/badge/PapersWithCode-Paper-green.svg?style=for-the-badge)](https://paperswithcode.com/paper/question-answering-model-for-schizophrenia)

## 📖 Overview

In recent years, the emphasis on mining medical data using machine learning techniques has grown exponentially. This project presents a new methodology for building a medical dataset and designing a QA model to analyze symptoms and their daily life impact for a specific disease domain. The main focus is on Schizophrenia, a mental disorder that affects millions worldwide.

## 📊 Dataset

The dataset originates from the "Mental Health" forum, dedicated to individuals suffering from schizophrenia and other mental disorders. The corpus consists of:
- 415,602 posts
- Respective IDs 
- Dates posted by different users

## 🛠 Tools & Techniques

- **Fine-tuned Models**: BERT, DistilBERT, RoBERTa, and BioBERT.
- **Haystack**: A framework for end-to-end QA systems.
- **Fine-tuning**: The models are rapidly fine-tuned for specific tasks with relatively fewer labels.

## 📈 Results

By fine-tuning the BioBERT QA model, we achieved:
- F1 Score: 0.885
- Notable improvement over state-of-the-art models in the mental disorders domain.

## 🤝 Contribution

We welcome contributions! Whether it's improving the model, enhancing the dataset, or providing feedback, feel free to make a pull request or open an issue.

## 📜 Citation

```bibtex
@misc{internò2023questionanswering,
      title={Question-Answering Model for Schizophrenia Symptoms and Their Impact on Daily Life using Mental Health Forums Data}, 
      author={Christian Internò and Eloisa Ambrosini},
      year={2023},
      eprint={2310.00448},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
