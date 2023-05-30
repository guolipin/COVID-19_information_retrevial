### Task
* Answer a user's query about COVID-19.
* Input: A user's query about COVID-19.
* Return: Top k relevant COVID-19 scholarly articles snippets.

### Data
Our data is a subset of [COVID-19 Open Research Dataset (CORD-19)](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge), including 10,000 academic articles.

### System Architecture
Our information retrieval system, also called search engine, is build based on the following architecture:

<img width="546" alt="image" src="https://github.com/guolipin/search_engine/assets/134791744/5203944e-5cd1-4d44-a484-335f65b3fe75">  

This image is from Jurafsky & Martin 2020, ch.14, p.2 [1].

### Versions
| Date | Code | Performance(MRR score) |
| :--- | :--- | :---|
||code|result1|
|22/03/23|version1|15.8%|

### Reference
[1] Jurafsky D & Martin JH 2020, Speech and Language Processing, 3rd ed., Stanford University, California, <https://web.stanford.edu/~jurafsky/slp3/>
