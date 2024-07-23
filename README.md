# SOP-Generator

Welcome to the SOP Generator Chatbot repository! This project aims to provide an interactive chatbot that can assist in generating Standard Operating Procedures (SOPs) using generative AI. The chatbot is built using Python and integrates various technologies to deliver an efficient and user-friendly experience.

## Features

- **Generative AI**: Uses `Mistral-7B-Instruct-v0.2` for language modeling.
- **Sentence Embeddings**: Utilizes `sentence-transformers/all-MiniLM-L6-v2` for embedding sentences.
- **Vector Database**: Implements ChromaDB for efficient data storage and retrieval.
- **User Interface**: Interactive interface built with Gradio.
- **Prompt Templates**: Customized prompt templates for generating specific SOP outputs.

## Instructions

The main Jupyter Notebook in this repository is:

- `SOP_Generation.ipynb`: This notebook contains all the code required to run the SOP generator chatbot, including data processing, model loading, and user interface setup.

## Setup
   
Open the Jupyter Notebook in Google Colab:

Navigate to the repository and open the SOP_Generation.ipynb file.

### Libraries Required:

Ensure you have the following libraries installed:

#### For Generative AI and Embeddings:

- sentence-transformers
- torch
- chromadb

#### For the User Interface: 

- gradio

## Usage

Run the Jupyter Notebook:

- Open the SOP_Generation.ipynb file in Google Colab.
- Run all cells in the notebook. This will launch the Gradio interface within the notebook.

Interact with the Chatbot:

- Use the Gradio interface to interact with the SOP Generation chatbot.

## Technologies Used

- Python
- Gradio: For building the user interface.
- Mistral-7B-Instruct-v0.2: For language modeling.
- sentence-transformers/all-MiniLM-L6-v2: For generating sentence embeddings.
- ChromaDB: Vector database for efficient data retrieval.

