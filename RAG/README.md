# Retrieval Augmented Generation Engine using LangChain & weaviate DB

[Kaggle Notebook](https://retrieval-augmented-generation.streamlit.app/)

![Demo](data/demo.gif)

## Overview

The Retrieval Augmented Engine (RAG) is a powerful tool for document retrieval, summarization, and interactive question-answering. This project utilizes LangChain and weaviate Db to provide a seamless web application for users to perform these tasks. With RAG, you can easily upload Your documents (Like PDF File, Json File, txt File etc.) and easily ask Questions related your Documents. 


## Features

- **Document Reading**: Users can upload multiple PDF files, which are then processed for further analysis.
- **Document's Text Splitting**: The uploaded PDFs are split into smaller text chunks, ensuring compatibility with models with token limits.
- **Vector Embeddings**: The text chunks are converted into vector embeddings using `OPENAI_API_KEY`, making it easier to perform retrieval and question-answering tasks.
- **Flexible Vector Storage**: You can choose to store vector embeddings either in weaviate or a local vector store, providing flexibility and control.

## Prerequisites

Before running the project, make sure you have the following prerequisites:

- Python 3.7+
- LangChain
- weaviate
- An OpenAI API key
- WEAVIATE_API_KEY and WEAVIATE_CLUSTER_URL
- Json File to upload (You can modily code and use other file)

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/chiragjoshi12/LangChain.git
   cd RAG
   ```

2. Open `Implementing a Retrieval-Augmented Generation (RAG) System with OpenAI's API + weaviate_DB.ipynb` File for use Weaviate Database

either 

2. Open `Implementing a Retrieval-Augmented Generation (RAG) System with OpenAI's API.ipynb` for use FAISS Database

## Contributors

[Chirag Joshi](https://github.com/chiragjoshi12)

## Contact

If you have any questions, suggestions, or would like to discuss this project further, feel free to get in touch with me:

- [LinkedIn](https://www.linkedin.com/in/chiragjoshi12/)

I'm open to collaboration and would be happy to connect!