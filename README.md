# Classification and recommend scientific articles based on contextual analysis of citations
#### 1) Introduction

This project performs citation classification and recommends articles related to the citation, this is a multi-task problem

#### 2) Dataset
We collected and constructed a dataset with 4167 labeled citations (include link of papers).

The citations were collected from scientific articles. 

Scientific articles are referenced from scientific research websites such as arXiv, ACL, NeurlPS, IEEEXplore,...

Each citations will include 3 labels which are described in detail in the data file.

#### 3) Technology

Tensorflow, Pytorch, nltk, sklearn,...

We fine-tuned BERT-base, Electra, DistilBERT for text classification task/citations classification (task 1), and using cosine similarity to recommend papers related to that citations (task 2)

Accuracy is 0.658 with DistilBERT for text classification task

#### 4) Demo

Input: a citiations

<img width="677" height="48" alt="image" src="https://github.com/user-attachments/assets/46a48734-b3ac-45af-8b40-3b9779ba8c62" />

Output task 1: Label of citiations

<img width="106" height="84" alt="image" src="https://github.com/user-attachments/assets/b6205bb9-3d44-42c7-a1b4-fc3cc2cfab76" />

Output task 2: Recommend k papers related to that label/citations using similarity measure

<img width="1225" height="169" alt="image" src="https://github.com/user-attachments/assets/4c2d4d33-1532-46b1-9f55-2fff37b772d9" />





