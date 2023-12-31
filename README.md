# Web-Chatbot

Overview
This chatbot is a sophisticated natural language processing system that leverages cutting-edge technologies such as Large Language Models (LLMs) from OpenAI, OpenAI Embeddings, LangChain Framework, and Faiss for efficient vector storage. The chatbot is designed to read entire websites, process the data, perform text embedding, and establish connections between questions, vector stores, and LLMs for comprehensive question-answering capabilities.

https://th.bing.com/th/id/OIP.nu7ZXSdSXeo6aCLEJYoZpgHaD4?rs=1&pid=ImgDetMain

Features
Website Reading:

Utilizes LangChain's UnstructuredURLLoader from the document_loaders module to read entire websites.
Data Processing:

Segments the website content into chunks using LangChain's CharacterTextSplitter from the text_splitter module.
Text Embedding:

Leverages LangChain's OpenAIEmbeddings from the embeddings module for text embedding using the OpenAI API.
Vector Storage:

Stores the embeddings efficiently using Faiss, a powerful similarity search and clustering library.
Integration of Components:

Establishes connections between questions, vector stores, and LLMs using LangChain's RetrievalQAWithSourcesChain from the chains module.
Question-Answering:

Utilizes LangChain's question-answering capabilities and loads the QA chain with load_qa_chain from the question_answering module.
OpenAI Integration:

Integrates OpenAI for enhanced language understanding and generation through LangChain's OpenAI module.
