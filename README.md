[![PapersWithCode](https://img.shields.io/badge/PapersWithCode-Paper-green.svg?style=for-the-badge)](https://paperswithcode.com/paper/question-answering-model-for-schizophrenia)

# Question-Answering-Model-for-Schizophrenia-Symptoms
Question-Answering Model for Schizophrenia Symptoms and Their Impact on Daily Life using Mental Health Forums Data


## Corpus
The original corpus consists of a list of 415602 posts with their respective IDs and dates posted by different users.

## Tutorial to fine tune a BERT model (from Haystack https://haystack.deepset.ai/overview/intro)
The model can be rapidly fine-tuned on a specific downstream task with relatively few labels.

## Final RoBERTa v2 trained model
RoBERTa is a transformers model pretrained on a large corpus of English data in a self-supervised way. This means it was pretrained on the raw texts only, with no humans labeling them in any way, with an automatic process to
generate inputs and labels from those texts.


## Question-Answering Model for Schizophrenia Symptoms and Their Impact on Daily Life using Mental Health Forums Data

In recent years, there is strong emphasis on mining medical
data using machine learning techniques. A common problem is to ob-
tain a noiseless set of textual documents, with a relevant content for the
research question, and developing a Question Answering (QA) model
for a specific medical field. The purpose of this paper is to present a
new methodology for building a medical dataset and obtain a QA model
for analysis of symptoms and impact on daily life for a specific disease
domain. The “Mental Health” forum was used, a forum dedicated to peo-
ple suffering from schizophrenia and different mental disorders. Relevant
posts of active users, who regularly participate, were extrapolated pro-
viding a new method of obtaining low-bias content and without privacy
issues. Furthermore, it is shown how to pre-process the dataset to convert
it into a QA dataset. The Bidirectional Encoder Representations from
Transformers (BERT), DistilBERT, RoBERTa, and BioBERT models
were fine-tuned and evaluated via F1-Score, Exact Match, Precision and
Recall. Accurate empirical experiments demonstrated the effectiveness
of the proposed method for obtaining an accurate dataset for QA model
implementation. By fine-tuning the BioBERT QA model, we achieved
an F1 score of 0.885, showing a considerable improvement and outper-
forming the state-of-the-art model for mental disorders domain.



![image](https://user-images.githubusercontent.com/80530899/228185010-d0bd5f41-2dea-419c-abf6-3197ef0c6625.png)



![image](https://user-images.githubusercontent.com/80530899/228185227-f33d866f-bf2f-4f8d-8751-4be2a2e6ee5b.png)



![image](https://user-images.githubusercontent.com/80530899/228185472-bbe242d6-4805-4d16-b9e4-513d5384192e.png)




![image](https://user-images.githubusercontent.com/80530899/228185796-975e438c-b125-46f0-932b-a9ee7500346c.png)




![image](https://user-images.githubusercontent.com/80530899/228185965-82d03b11-2035-49d4-b5a9-3102c640ff4c.png)

## Experiments result
Models Precision F1 Recall EM
DistilBERT 0.681 0.639 0.713 0.425
RoBERTa 0.746 0.743 0.7724 0.425
BioBERT 0.790 0.775 0.880 0.427
Fine-tuned-DistilBERT 0.805 0.783 0.831 0.438
Fine-tuned-RoBERTa 0.885 0.803 0.861 0.508
Fine-tuned-BioBERT 0.903 0.885 0.916 0.617

![image](https://user-images.githubusercontent.com/80530899/228186051-44ec625e-1594-4f5c-ac15-d39cd4b122c4.png)

