# Building a Blog AI assistant using Retrieval Augmented Generation

## Overview

In this guide, we will build an LLM Chatbot that uses Retrieval Augmented Generation to answer questions about a particular blog or a list of blogs. We use LlamaIndex to chunck the blog text and build index, and then provide this context from the blog chunks along with the prompt to the GPT-4 model to build the chatbot.

By the end of this session, you will have an interactive web application deployed that helps answer questions from the blog.

## Step-By-Step Guide

Install requirements: pip install -r requirements.txt
Create data: python data_pipeline.py
Build data index: python build_index.py
Run app: streamlit run streamlit_app.py