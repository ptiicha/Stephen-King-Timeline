# 📚 Stephen-King-Timeline
![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Status](https://img.shields.io/badge/Project-Stephen_King_Timeline-brightgreen)

A data science project that visualizes Stephen King's bibliography and explores books using semantic similarity, plot summaries, and an interactive search dashboard.
In progress...

## 💬 Overview
This project builds a horizontal timeline of Stephen King's books with:
- Cover images
- Publication years
- Goodreads ratings

Additionally, it includes:
- A recommendation system based on semantic plot similarity
- Short plot summaries generated with Transformer-based models
- An integrated Gradio-powered search interface

## ✨ Features 
- Sentence-transformers for semantic similarity between books
- Plot summarization using BART (facebook/bart-large-cnn)
- Top-3 similar books shown on hover
- Search interface with book finder by theme/keyword
- Responsive HTML+CSS layout with ratings, popups, and embedded Gradio iframe

## 🚀 Technologies Used
- Python: pandas, nltk, transformers, sentence-transformers, scikit-learn, tqdm
- Visualization: HTML, CSS, Gradio, Jupyter Notebook
- Deployment: Netlify (static dashboard), Gradio (search backend)

## 🧠 Models
- all-mpnet-base-v2 for sentence embeddings
- facebook/bart-large-cnn for summarization

## 🔄 Deployment
The static dashboard (index.html) is deployed on Netlify.
The Gradio search app runs locally or can be deployed separately via Hugging Face Spaces.

![Repo Visitors](https://visitor-badge.laobi.icu/badge?page_id=ptiicha/Stephen-King-Timeline/)
  
🌐 Dashboard: [Live Site on Netlify](https://stephenkingtimeline.netlify.app/)

📈 Visitors: 
