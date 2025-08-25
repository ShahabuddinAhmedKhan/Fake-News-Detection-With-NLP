# Fake News Detection

This project is designed to detect fake news using various Natural Language Processing (NLP) techniques. The model analyzes text data to predict whether the news is real or fake.

## Requirements

Before running the code, set up the environment by following these steps:

### Step 1: Clone the Project
Clone the repository to your local machine:
```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
```

### Step 2: Set Up the Conda Environment, Dependencies

```bash
conda create --name [ENVIRONTMENT NAME] python=3.11
conda activate [ENVIRONTMENT NAME]
pip install nltk==3.9.1 pandas==2.2.3 matplotlib==3.10.0 spacy==3.8.3 textblob==0.18.0.post0 vaderSentiment==3.3.2 transformers==4.47.1 scikit-learn==1.6.0 gensim==4.3.3 seaborn==0.13.2 torch==2.5.1 ipywidgets==8.1.5
python -m spacy download en_core_web_sm
pip install ipykernel jupyterlab notebook
python -m ipykernel install --user --name=[ENVIRONTMENT NAME]
```
