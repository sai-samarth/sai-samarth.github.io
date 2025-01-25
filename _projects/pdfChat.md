---
layout: page
title: Chat with Your PDF
description: Streamlit application to interactively chat with PDF documents.
img: assets/img/ChatPDF.jpg
importance: 1
category:
related_publications: False
---

## Chat with Your PDF

This Streamlit application enables users to chat directly with their PDF files, making it easy to ask questions about their documents. It works by first extracting textual content from the provided PDF, then creating meaningful embeddings using either OpenAI or local HuggingFace Embeddings (note: using the latter can be slightly slower). The application performs a semantic search based on the user's query, and the results are passed to a Large Language Model (LLM) like OpenAI's ChatGPT, Llama 2, or models available on the Hugging Face Hub. Utilizing Langchain ensures that conversation memory is retained through Langchain's Memory Buffer, providing a cohesive chatting experience. The response from the LLM is then presented back to the user.

**Features:**

- **Document Upload:** Quickly upload multiple PDF files to chat with.
- **Multiple Embedding Support:** Choose between OpenAI or HuggingFace Embeddings.
- **Semantic Search:** Enhanced search capability that understands the context of the user's query.
- **Integration with LLMs:** Integrated with popular models like OpenAI's ChatGPT, Llama 2, and models from Hugging Face Hub.
- **Conversation Memory:** Thanks to Langchain's Memory Buffer, the application remembers the conversation, providing a cohesive chatting experience.

Check out the project on GitHub [here.](https://github.com/sai-samarth/ChatWithYourPDF)
