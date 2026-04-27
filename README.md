# TF-IDF Word Importance Analysis

## Description
This project computes Term Frequency–Inverse Document Frequency (TF-IDF) scores for a collection of text documents to identify the most important words across the corpus.

The project demonstrates how TF-IDF can be used to measure word importance by balancing term frequency within documents against overall frequency across documents.

---

## Problem Statement
In textual datasets, not all words contribute equally to document meaning. Frequently occurring words across all documents may be less informative than words unique to specific documents.

TF-IDF helps identify the most significant terms in a document collection.

---

## Objective
- Preprocess text documents  
- Remove common stopwords  
- Compute TF, IDF, and TF-IDF scores  
- Identify top important words  
- Visualize TF-IDF scores of top terms  

---

## Dataset / Input
The project uses three predefined sample documents:

1. AI is the future of technology  
2. AI and machine learning are important  
3. Technology is evolving with AI  

---

## Methodology
1. Input documents are preprocessed  
2. Stopwords are removed  
3. TF-IDF Vectorizer computes TF-IDF matrix  
4. Overall term scores are aggregated  
5. Top words are extracted and visualized  

---

## Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## Output
The project generates:
- TF-IDF Matrix  
- Top 5 Important Words  
- Bar Chart of TF-IDF Scores  

---

## Applications
- Keyword Extraction  
- Search Engine Ranking  
- Document Summarization  
- Text Classification Feature Engineering  

---

## Future Improvements
- Support user-uploaded document collections  
- Add per-document TF-IDF comparison  
- Include n-gram TF-IDF analysis  
