# Unsupervised Topic Segmentation of Meetings.
This repo contains NLP course project. Different solutions were considered, the article (https://arxiv.org/abs/2106.12978) was implemented, the results of different approaches on test datasets were obtained.

Approaches used:
- BERT
- SBERT
- Random
- Even
- XLM
- TextTiling

Here it is our results:

| **Model**                           | **AMI PK** | **AMI WD** | **ICSI PK** | **ICSI WD** | **Own PK** | **Own WD** |
|------------------------------------------|-----------------|-----------------|------------------|------------------|-----------------|-----------------|
| **BERT (RoBERTa base)**            | 0.462           | 0.474           | 0.482            | 0.511            | 0.49            | 0.53            |
| **BERT (multilingual-uncased)**     | 0.449           | 0.464           | 0.43             | 0.456            | 0.47            | 0.47            |
| **BERT (multilingual-cased)**       | 0.451           | 0.469           | 0.423            | 0.453            | 0.45            | 0.48            |
| **XLM (with language embeddings)**  | 0.44            | 0.456           | 0.443            | 0.478            | 0.48            | 0.49            |
| **XLM (RoBERTa base)**              | 0.452           | 0.47            | 0.474            | 0.502            | 0.5             | 0.52            |
| **SBERT (all-mpnet-base-v2)**       | 0.457           | 0.48            | 0.468            | 0.519            | 0.49            | 0.53            |
| **SBERT (paraphrase-multilingual)** | 0.457           | 0.48            | 0.467            | 0.521            | 0.49            | 0.5             |
| **Random**                          | 0.609           | 0.762           | 0.645            | 0.844            | 0.79            | 0.83            |
| **Even**                            | 0.523           | 0.557           | 0.614            | 0.671            | 0.67            | 0.74            |
| **TextTiling**                     | 0.394           | 0.41            | 0.384            | 0.406            | 0.44            | 0.45            |
| **Paper implementation**            | **0.339**  | **0.334**  | **0.336**   | **0.349**   | **0.35**   | **0.4**    |
