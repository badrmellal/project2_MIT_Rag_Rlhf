# MIT RAG System with RLHF

A Retrieval-Augmented Generation (RAG) system with Reinforcement Learning from Human Feedback (RLHF) capabilities for document analysis and question answering.

## Overview

This project implements a complete RAG system that:
- Processes PDF, DOCX, and TXT documents
- Chunks text intelligently
- Embeds text using a multilingual model
- Retrieves relevant context for queries
- Generates answers using a Hugging Face LLM
- Learns from user feedback to improve over time

## Installation

### Requirements
- Python 3.8+
- **Google Colab environment** (strongly recommended as this project was developed and tested in Colab)
- GPU runtime recommended for faster embedding and inference
- 8GB+ RAM (16GB+ recommended for larger documents)

### Setup in Google Colab (Recommended)

1. Open the notebook in Google Colab:
   - Visit [Google Colab](https://colab.research.google.com/)
   - Create a new notebook or upload the `MIT_RAG_System.ipynb` file
   - Or open directly from GitHub: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/badrnellal/project2_MIT_Rag_Rlhf/blob/main/MIT_RAG_System.ipynb)
   
2. The notebook includes all necessary installation commands. Run the first cell to install dependencies:
   ```python
   !pip install -q chromadb sentence-transformers transformers ipywidgets==7.7.1 scikit-learn pandas matplotlib seaborn PyPDF2 python-docx tiktoken
