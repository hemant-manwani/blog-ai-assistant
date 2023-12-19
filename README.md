
# Building a Blog AI assistant using Retrieval Augmented Generation

## Overview

In this guide, we will build an LLM Chatbot that uses Retrieval Augmented Generation to answer questions about a particular blog or a list of blogs. We use LlamaIndex to chunck the blog text and build index, and then provide this context from the blog chunks along with the prompt to the GPT-4 model to build the chatbot.

By the end of this session, you will have an interactive web application deployed that helps answer questions from the blog.

## Step-By-Step Guide

**Install requirements:** pip install -r requirements.txt

**Create data:** python data_pipeline.py

**Build data index:** python build_index.py

**Run app:** streamlit run streamlit_app.py

<img width="1319" alt="Screenshot 2023-12-19 at 11 40 24 AM" src="https://github.com/hemant-manwani/blog-ai-assistant/assets/10157792/39dd1530-a25c-4fe6-b712-4656dc621bcb">
