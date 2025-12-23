# Sentiment Analysis & Influence Detection using BERTweet and Graph-RAG

This project presents an end-to-end system for sentiment analysis and influence detection on social media data, combining Natural Language Processing (NLP) and graph-based learning techniques.

The objective is not only to classify tweet sentiment, but also to model user interactions and influence using a graph structure enriched with contextual retrieval (Graph-RAG).

---

## 🔍 Project Overview

The pipeline is composed of four main stages:

1. **Tweet-level Sentiment Analysis**  
   - Fine-tuning of **BERTweet** for sentiment classification  
   - Prediction of sentiment polarity on social media text

2. **Graph Construction**  
   - Heterogeneous graph modeling users, tweets, and interactions  
   - Edges represent relations such as authorship and mentions

3. **Graph-based Reasoning & Influence Analysis**  
   - Community detection
   - Ego-network and subgraph extraction
   - Identification of influential users

4. **Graph-RAG (Retrieval-Augmented Generation)**  
   - Contextual retrieval from graph neighborhoods
   - Enhanced analysis using graph-aware information

---

## 🧠 Technologies & Tools

- Python
- PyTorch
- PyTorch Geometric
- Hugging Face Transformers (BERTweet)
- NetworkX
- NLP & Graph Neural Networks
- HTML / Interactive visualizations

---

## 📊 Key Features

- Sentiment classification of tweets
- User-level sentiment aggregation
- Social graph construction
- Influence and community analysis
- Interactive visual outputs (ego networks, communities, pipelines)

---

## 📁 Project Structure

sentiment-analysis-graph-rag/
│
├── notebooks/ # Training and analysis notebooks
│ ├── Sentiment_Analysis_Using_Bertweet.ipynb
│ └── Graph_Rag.ipynb
│
├── outputs/ # Generated HTML visualizations
│ ├── pipeline.html
│ ├── prediction.html
│ ├── ego_network.html
│ ├── community.html
│ └── subgraph.html
│
├── config/ # Configuration files
│
├── README.md
└── requirements.txt

---

## 🚀 How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt
Run the notebooks in the following order:

Sentiment_Analysis_Using_Bertweet.ipynb

Graph_Rag.ipynb

⚠️ Model Weights

The fine-tuned model weights are not included in this repository due to size constraints.
They can be provided upon request.

👥 Authors & Contributions

This project was developed as a collaborative academic project.

Contributors:

Wassim Azaiez

Dhia Eddine Jedidi


My contributions focused on:

Graph modeling and analysis

Graph-RAG pipeline design

Result interpretation and visualization

🎯 Context

This project was carried out in an academic context and is aligned with advanced topics in:

Applied NLP

Graph Neural Networks

Retrieval-Augmented Generation (RAG)

Social network analysis

It is intended as a foundation for further research or industrial applications.


---
