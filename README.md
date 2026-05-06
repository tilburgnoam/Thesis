# Fine-grained Aspect-Based Sentiment Analysis of the Hamas-Israel Conflict on X

This repository contains the full codebase and analysis pipeline for the thesis:

## Fine-grained Aspect-Based Sentiment Analysis of the Hamas-Israel Conflict on X

By Noam Ladani, Tilburg University, 2026



## Abstract
This study applies fine-grained (5-class) Aspect-Based Sentiment Analysis (ABSA) 
to tweets related to the Hamas-Israel attack on October 7th 2023. 
Traditional machine learning, deep learning, and transformer-based models 
(BERT, RoBERTa, DeBERTa-v3) are compared using macro-F1 score, 
with LIME explainability analysis across model families.

## Models
- Traditional ML: Complement Naive Bayes, Linear SVM, Logistic Regression
- Deep Learning: CNN, GRU, BiLSTM 
- Transformers: BERT, RoBERTa, DeBERTa-v3

## Dataset
HIC Dataset by Xie & He (2025) — publicly available at:
https://github.com/HarveyXYZ/OpenNOD/tree/main


## Requirements
- Python 3.12.13
- Scikit-learn
- Keras/TensorFlow
- HuggingFace Transformers
- LIME

## Thesis
Submitted in partial fulfillment of the MSc Data Science & Society
Tilburg University, 2026





# Repository Structure
Thesis/
├── Preprocessing_EDA.ipynb

├── Thesis_Machine_Learning.py

├── Thesis_Deep_Learning.py

├── Thesis_BERT.py

├── Thesis_RoBERTa.py

├── Thesis_DeBERTa-v3.py

├── LICENSE

├── .gitignore
└── README.md








## Citation
If you use this code, please cite:

```
@mastersthesis{ladani2025absa,
  title={Fine-grained Aspect-Based Sentiment Analysis of the Hamas-Israel Conflict on X},
  author={Noam Ladani},
  school={Tilburg University},
  year={2026},
  url={https://github.com/tilburgnoam/Thesis}
}
```
