# Food For Thought
AI chatbot for restaurants 

## Goal: 
To create an AI Chatbot Application that uses Retrieval Augumented Generation (RAG) in Ollama Langflow (GUI implementation of Langchain) to manage restaurant FAQs

## Setup/Installation:

### Update python through homebrew (for macOS):  

#### &emsp; Install home brew:
&emsp;&emsp; /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

#### &emsp; Update homebrew:
&emsp;&emsp; brew update

#### &emsp; Update python:
&emsp;&emsp; brew upgrade python  

### Download langflow:
&emsp; python3 -m pip install langflow -U

### Run langflow:
&emsp; python3 -m langflow run

### Download Ollama (for macOS):
&emsp; https://ollama.com/

### Start Ollama in the background:
&emsp; ollama serve

### Use the latest version:
&emsp; Ollama pull llama2

### Upload the Entity Relationship Diagram (ERD):
&emsp; Use the JSON file to create playground

### Connect a vectorized database:

#### &emsp; Create an astradb database on datastax:
&emsp;&emsp; https://www.datastax.com/products/datastax-astra  

#### &emsp; Details:
&emsp;&emsp; database type: serverless (vector)  
&emsp;&emsp; server: aws/gcp server  
&emsp;&emsp; name: langflow_db  
&emsp;&emsp; region: us-east-2/us-east1  

### Feeding data:
&emsp; Copy the API endpoint and application tokens and paste in the corresponding fields in ERD

### Run the program:
&emsp; Use the play button to build the program  
&emsp; Click on playground button to launch chatbot

## Dependencies:
&emsp; Langflow  
&emsp; Ollama

## Python version:
&emsp; 3.10

## Next Steps:
&emsp; Implement program in langchain
