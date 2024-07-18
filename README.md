# LLM RAG for restaurants 

## Goal: 
To create an AI Application that uses Retrieval Augumented Generation (RAG) in Langflow (GUI implementation of Langchain)

## Setup/Installation:

### Update python through homebrew (for macOS):

#### Install home brew:
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

#### Update homebrew:
brew update

#### Update python:
brew upgrade python

### Download langflow:
python3 -m pip install langflow -U

### Run langflow:
python3 -m langflow run

### Download Ollama (for macOS):
https://ollama.com/

### Start Ollama in the background:
ollama serve

### Use the latest version:
Ollama pull llama2

### Upload the Entity Relationship Diagram (ERD):
Use the JSON file to create playground

### Connect a vectorized database:

#### Create an astradb database on datastax:
https://www.datastax.com/products/datastax-astra

#### Details:
database type: serverless (vector)
server: aws/gcp server
name: langflow_db
region: us-east-2/us-east1

### Feeding data:
Copy the API endpoint and application tokens and paste in the corresponding fields in ERD

## Dependencies:
Langflow
Ollama

## Python version:
3.10
