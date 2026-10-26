# JavaMentor AI

## Overview

JavaMentor AI is an AI-powered assistant built with n8n that answers users' questions about Java programming using information retrieved from a PDF document and scraped website content.

The project uses Retrieval-Augmented Generation (RAG) to provide context-aware answers based on external knowledge sources.

## Features

- Answers questions about Java programming.
- Retrieves relevant information from PDF documents.
- Uses scraped website content as an additional knowledge source.
- Generates answers using a chat model.
- Automates the question-answering process through n8n.

## Technologies

- n8n
- Large Language Model (LLM)
- Retrieval-Augmented Generation (RAG)
- PDF document processing
- Web scraping

## How It Works

1. The user submits a question about Java.
2. The workflow retrieves relevant information from the PDF and scraped website content.
3. The retrieved information is provided to the chat model.
4. The model generates an answer based on the available context.

## Setup

1. Import the workflow JSON file into n8n.
2. Configure the required credentials and API keys.
3. Ensure the PDF and scraped website content are available to the retrieval system.
4. Execute the workflow and test it with Java-related questions.

## Security

Credentials and API keys must be configured separately in n8n. Do not publish sensitive information in this repository.

## Author

Developed as a practical project exploring AI agents, RAG, and workflow automation.
