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

### Upload the ERD:
Use the JSON file to create playground and then click on the run button to run the application

## Dependencies:
Langflow
Ollama

## Python version:
3.10
