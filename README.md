[![PapersWithCode](https://img.shields.io/badge/PapersWithCode-Paper-green.svg?style=for-the-badge)](https://paperswithcode.com/paper/question-answering-model-for-schizophrenia)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/question-answering-model-for-schizophrenia/question-answering-on-schizzosquad)](https://paperswithcode.com/sota/question-answering-on-schizzosquad?p=question-answering-model-for-schizophrenia)
# Question-Answering-Model-for-Schizophrenia-Symptoms

Question-Answering Model for Schizophrenia Symptoms and Their Impact on Daily Life using Mental Health Forums Data

> **Citation**:
>
> @misc{internò2023questionanswering,
>      title={Question-Answering Model for Schizophrenia Symptoms and Their Impact on Daily Life using Mental Health Forums Data}, 
>      author={Christian Internò and Eloisa Ambrosini},
>      year={2023},
>      eprint={2310.00448},
>      archivePrefix={arXiv},
>      primaryClass={cs.LG}
> }

## Corpus

The original corpus consists of a list of 415602 posts with their respective IDs and dates posted by different users.

## Tutorial to fine tune a BERT model (from [Haystack](https://haystack.deepset.ai/overview/intro))
The model can be rapidly fine-tuned on a specific downstream task with relatively few labels.

## Final RoBERTa v2 trained model

RoBERTa is a transformers model pretrained on a large corpus of English data in a self-supervised way. This means it was pretrained on the raw texts only, with no humans labeling them in any way, with an automatic process to generate inputs and labels from those texts.

## Background

In recent years, there is strong emphasis on mining medical data using machine learning techniques. A common challenge is to obtain a pristine set of textual documents, with content relevant to the research question, and developing a Question Answering (QA) model for a specific medical domain. This paper introduces a novel methodology for curating a medical dataset and crafting a QA model to analyze symptoms and the impact on daily life for a specific disease domain. We utilized the “Mental Health” forum, dedicated to individuals with schizophrenia and other mental disorders. By extracting posts from active, regular participants, we've introduced a method to obtain unbiased content while addressing privacy concerns. We also outline the preprocessing steps to transform this data into a QA dataset. The Bidirectional Encoder Representations from Transformers (BERT), DistilBERT, RoBERTa, and BioBERT models were refined and evaluated based on F1-Score, Exact Match, Precision, and Recall metrics. Through meticulous empirical experiments, we've demonstrated the efficacy of our methodology in procuring a reliable dataset for QA model development. Our fine-tuned BioBERT QA model achieved an F1 score of 0.885, marking a significant advancement and surpassing the prevailing models in the mental disorders domain.

![image](https://user-images.githubusercontent.com/80530899/228185010-d0bd5f41-2dea-419c-abf6-3197ef0c6625.png)

![image](https://user-images.githubusercontent.com/80530899/228186051-44ec625e-1594-4f5c-ac15-d39cd4b122c4.png)
