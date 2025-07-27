# ITC6110 – Natural Language Processing Final Portfolio
**Course:** ITC6110 – Natural Language Processing

**Institution**: MSc in Data Science, the American College of Greece

**Term:** Spring 2024

This repository presents a structured collection of NLP assignments and deliverables completed during the Fall 2023 semester. 

Each folder reflects one core topic, ranging from word embeddings to machine translation and custom NER pipelines.

# Project Structure
```
.
├── 1. embeddings/
├── 2. context_embeddings/
├── 3. text_classification/
├── 4. sentiment_classification/
├── 5. machine_translation/
├── 6. sample_custom_ner/
├── 7. deliverables/
└── README.md
```

# Folder Descriptions
| Folder                         | Description                                                                                                       |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| `1. embeddings/`               | Static word embeddings via Word2Vec, FastText, GloVe; evaluates cosine similarity and analogy tasks.              |
| `2. context_embeddings/`       | Contextual embeddings (ELMo, BERT); comparisons of token representations across contexts.                         |
| `3. text_classification/`      | Classical and neural models for text classification; includes Naive Bayes, SVM, and simple NN.                    |
| `4. sentiment_classification/` | Sentiment analysis on IMDb reviews using transformers (BERT, RoBERTa).                                            |
| `5. machine_translation/`      | Sequence-to-sequence model for English→German translation using PyTorch. Dataset: custom TSV format.              |
| `6. sample_custom_ner/`        | Custom named entity recognition (NER) using spaCy with a focus on COVID-related categories and JSON-labeled data. |
| `7. deliverables/`             | Final presentation materials and summary PDFs.                                                                    |


# How to Run (General)
1. Clone the repo.
2. Install dependencies.
3. Open .ipynb files from each folder in Jupyter or VSCode and follow the cells.

# Requirements
This project relies on the following major packages:

```
numpy
pandas
scikit-learn
matplotlib
seaborn
nltk
spacy
transformers
torch
sentencepiece
bs4
```

# Notes
1. Code in each folder runs independently.
2. Folder `6. sample_custom_ner/` includes `annotations_dataset/`, `config/`, and `my_categories/` used to train and test spaCy NER pipelines.
3. Folder `5. machine_translation/` includes a small paired English–German dataset.
