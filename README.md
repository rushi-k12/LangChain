# LangChain

LangChain is a project aimed at building a question answering system using language models and vector similarity search. It utilizes various NLP techniques and models to provide accurate and relevant answers to user queries.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [License](#license)

## Introduction

LangChain is designed to provide a user-friendly interface for querying a knowledge base and retrieving relevant information. It leverages language models like Google Palm and vector similarity search techniques to match user queries with the most appropriate answers.

## Features

- Question Answering System: LangChain can answer user queries by matching them with the closest context in the knowledge base.
- Vector Similarity Search: It uses vector embeddings to perform efficient similarity search for retrieving relevant information.
- Customizable: LangChain can be extended with additional language models and data sources to enhance its capabilities.

## Usage
To use LangChain, follow these steps:

Prepare your knowledge base:

Prepare a CSV file containing the context and corresponding questions and answers.

Create a vector database:

Use the create_vector_db() function to create a vector database from the knowledge base.

Start the LangChain server:

Run the Streamlit app using the main.py script.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
