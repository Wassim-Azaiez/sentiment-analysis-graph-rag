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

