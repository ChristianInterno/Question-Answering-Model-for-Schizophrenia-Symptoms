# 🧠 Question-Answering Model for Schizophrenia Symptoms

![QA Header]([[https://images.unsplash.com/photo-1567427017947-545c5f8d16ad?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80](https://assets.aboutamazon.com/dims4/default/2d07242/2147483647/strip/true/crop/1919x1080+1+0/resize/1320x743!/format/webp/quality/90/?url=https%3A%2F%2Famazon-blogs-brightspot.s3.amazonaws.com%2F21%2Fd3%2F171c031b4871a367060f2b974a59%2Fhealth-hero-1.jpg)](https://images.unsplash.com/photo-1564121211835-e88c852648ab?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1740&q=80))

> **A deep dive into the world of Schizophrenia through the lens of Machine Learning.** 

This repository is dedicated to understanding Schizophrenia symptoms and their impact on daily life, leveraging vast data from mental health forums and advanced ML models.

[![PapersWithCode](https://img.shields.io/badge/PapersWithCode-Paper-green.svg?style=for-the-badge)](https://paperswithcode.com/paper/question-answering-model-for-schizophrenia)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/question-answering-model-for-schizophrenia/question-answering-on-schizzosquad)](https://paperswithcode.com/sota/question-answering-on-schizzosquad?p=question-answering-model-for-schizophrenia)

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
