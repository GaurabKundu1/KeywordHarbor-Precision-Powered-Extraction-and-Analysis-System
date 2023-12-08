# KeywordHarbor: Precision Powered Extraction and Analysis System

## Created by : [Gaurab Kundu](https://www.linkedin.com/in/gaurab-kundu/)

## Introduction

KeywordHarbor is a sophisticated natural language processing (NLP) and machine learning system designed to automatically identify and extract the most important or representative words and phrases from text. This README provides an overview of the importance of keyword extraction, the techniques employed by KeywordHarbor, and the challenges it addresses.

## Importance of Keyword Extraction

### 1. Summarization and Understanding

Keyword extraction enables the summarization and understanding of text documents without the need to read them fully. By identifying key terms, users can quickly grasp the main themes and topics discussed in the text.

### 2. Categorization and Organization

Keyword extraction aids in categorizing and organizing documents based on their topics or themes. This functionality is valuable for content management and organization.

### 3. Information Retrieval and SEO

The system assists in information retrieval, indexing, and search engine optimization (SEO) by improving search relevance and accuracy. Relevant keywords enhance the discoverability of documents in search engines.

### 4. Text Mining and Sentiment Analysis

Keyword extraction is valuable for text mining and sentiment analysis, enabling the identification of significant words or phrases for further analysis and insights.

## Techniques for Keyword Extraction

KeywordHarbor employs various techniques to extract keywords from text:

### 1. Frequency-based Methods

Frequency-based methods rely on word or phrase occurrences within the text. Common approaches include Term Frequency-Inverse Document Frequency (TF-IDF), term frequency (TF), and inverse document frequency (IDF).

### 2. Graph-based Methods

Graph-based approaches represent text as a graph, with words/phrases as nodes and their relationships as edges. Algorithms like TextRank or PageRank identify important nodes as keywords based on co-occurrence.

### 3. Machine Learning Methods

KeywordHarbor utilizes supervised or unsupervised machine learning techniques for keyword extraction. These methods involve training models on annotated data or learning patterns from the text to identify significant words or phrases.

### 4. Rule-based Methods

Rule-based approaches employ predefined linguistic rules, patterns, or heuristics to identify keywords. These rules may consider syntactic structures, part-of-speech tags, or specific domain knowledge.

## Challenges in Keyword Extraction

KeywordHarbor addresses several challenges in keyword extraction:

### 1. Polysemy and Ambiguity

The system handles words with multiple meanings or ambiguous terms by incorporating contextual understanding to improve accuracy.

### 2. Domain-Specificity

Keywords may vary depending on the domain or topic. KeywordHarbor allows the creation of domain-specific lexicons or models to enhance extraction accuracy.

### 3. Noisy or Irrelevant Words

Extraction methods filter out irrelevant or noisy words, such as stop words or highly frequent words, to focus on those carrying significant meaning.

### 4. Co-reference Resolution

KeywordHarbor improves extraction quality by resolving co-references, linking pronouns or referring expressions to their respective entities.

## Getting Started

Follow these steps to get started with KeywordHarbor:

1. Clone the repository, by running the following command in a terminal

```
git clone https://github.com/GaurabKundu1/KeywordHarbor-Precision-Powered-Extraction-and-Analysis-System.git
```
2. Now go to the cloned repository on your local machine and Download all the dependencies by running the following command in a terminal

```
pip install -r requirements.txt
```

3. Download the Dataset from this [Link](https://www.kaggle.com/datasets/benhamner/nips-papers)

You only nedd the papers.csv

4. Now Run all the cells of KeyWord_Extraction.ipynb file to generate count_vectorizer.pkl, feature_names.pkl and tfidf_transformer.pkl files respectively.

5. Now in a Terminal Run the following command to run the app.

```
python -m flask run
```

It should say Running on http://127.0.0.1:5000

Go to http://127.0.0.1:5000 in your Browser to access the app.

Here is a sneakpeak of the app

<img src="https://github.com/GaurabKundu1/KeywordHarbor-Precision-Powered-Extraction-and-Analysis-System/assets/86102231/d352454d-c58d-4c05-9c6c-cc0df7b1fdb3">
