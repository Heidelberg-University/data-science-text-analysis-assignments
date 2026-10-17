# Data Science for Text Analysis Assignments

Team solutions to the four assignments of the Data Science for Text Analysis course, covering information extraction, text mining with Elasticsearch, word embeddings, text classification, keyphrase extraction and named entity recognition.

| | |
|---|---|
| Course | Data Science for Text Analysis |
| University | Heidelberg University, M.Sc. Data and Computer Science |
| Semester | Winter 2022/23 |
| Type | Team assignments |

## Assignments

| Folder | Topic | Main tools |
|---|---|---|
| `Assignment_1/` | Regular expression validation and text extraction from PDF documents, compared with `SequenceMatcher` | Python, PyPDF2, pypdfium2, LaTeX |
| `Assignment_2/` | Elasticsearch and text mining on "The Simpsons" dataset (characters, locations, episodes and script lines) | pandas, spaCy, scikit-learn, wordcloud |
| `Assignment_3/` | Text classification and word embeddings, including a Word2Vec model trained on Friends transcripts | Gensim, spaCy, scikit-learn, seaborn |
| `Assignment_4/` | Keyphrase extraction, named entity recognition and neural models | spaCy |

## Getting started

The assignments were written for Python 3.7. Each assignment is a Jupyter notebook; where a `requirements.txt` exists, install it first:

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -r Assignment_1/requirements.txt
jupyter notebook
```

## Team

Kushal Gaywala, Rishabh Tiwari, Jakob Forstmann and Jonathan Hirsch.
