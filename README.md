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
│
├── README.md
│
├── preprocessing_EDA/
│   └── preprocessing_eda.ipynb
│
├── ML/
│   └── ml_models.ipynb
│
├── DL/
│   └── dl_models.ipynb
│
└── Transformers/
    ├── BERT/
    │   └── bert.ipynb
    ├── RoBERTa/
    │   └── roberta.ipynb
    └── DeBERTa/
        └── deberta.ipynb





## File Descriptions

| File | Description |
|------|-------------|
| preprocessing_EDA/preprocessing_eda.ipynb | Data preprocessing and exploratory data analysis |
| ML/ml_models.ipynb | Traditional ML models (CNB, Linear SVM, Logistic Regression) with TF-IDF and LIME analysis |
| DL/dl_models.ipynb | Deep learning models (CNN, GRU, BiLSTM) with FastText embeddings and LIME analysis |
| Transformers/BERT/bert.ipynb | BERT fine-tuning and evaluation with LIME analysis |
| Transformers/RoBERTa/roberta.ipynb | RoBERTa fine-tuning and evaluation with LIME analysis |
| Transformers/DeBERTa/deberta.ipynb | DeBERTa-v3 fine-tuning and evaluation with LIME analysis |




## Citation
If you use this code, please cite:

```
@mastersthesis{ladani2025absa,
  title={Fine-grained Aspect-Based Sentiment Analysis of the Hamas-Israel Conflict on X},
  author={Noam Ladani},
  school={Tilburg University},
  year={2025},
  url={https://github.com/[your-username]/Thesis}
}
```
