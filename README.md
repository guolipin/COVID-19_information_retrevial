### Task
* Answer a user's query about COVID-19.
* Input: A user's query about COVID-19.
* Return: Top k relevant COVID-19 scholarly articles.

### Data
Our data is a subset of [COVID-19 Open Research Dataset (CORD-19)](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge), including 10,000 academic articles.

### System Architecture
Our information retrieval system, also called search engine, is build based on the following architecture:

<img width="546" alt="image" src="https://github.com/guolipin/search_engine/assets/134791744/5203944e-5cd1-4d44-a484-335f65b3fe75">  

This image is from Jurafsky & Martin 2020, ch.14, p.2 [1].

### Versions
| Date | Code | Performance(MRR score) |
| :---: | :---: | :---: |
|19/04/23|[version2](https://github.com/guolipin/search_engine/blob/main/search_engine_v2.ipynb)|75%🚀|
|22/03/23|[version1](https://github.com/guolipin/search_engine/blob/main/search_engine_v1.ipynb)|65%|

- version 2 fixs some bugs in version 1 and also uses a faster retrevial method to find relevant articles.

### Performance
**Metric**  
MRR stands for Mean Reciprocal Rank, and it is a measure used to evaluate the effectiveness of a search engine algorithm. IMRR measures the average rank of the first relevant result in a set of search results, where each rank is weighted by its reciprocal value.

**Runtime**  
Version 1 uses slow article retrieval method, while version 2 uses the fast one.  

<img width="350" alt="image" src="https://github.com/guolipin/search_engine/assets/134791744/44d850b5-05ac-4a9f-bdef-bb5131c212e0">



### Requirements
Due to the data files are large, I am not able to upload it at the moment.
* To run code successfully, you need to download data from Kaggle (20G) and sample it following my code instruction. 
* To run code efficiently, I recommend you to save csv file or json file in the same directory, which will save 1-2 hours for data processing.

### Reference
[1] Jurafsky D & Martin JH 2020, Speech and Language Processing, 3rd ed., Stanford University, California, <https://web.stanford.edu/~jurafsky/slp3/>
