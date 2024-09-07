# mini-rag
This is a minimal implementation of the RAG model for question answering.

## Requirements

- python 3.8 or later

### install python using mini conda

1) download and install Mini conda ()

2) create a new environment using the following command:
''' bash
$ conda create -n ENV-NAME python=3.8 
'''
3) activate the enviroment:
''' bash
$conda activate ENV-NAME
'''

## Installation
### Install the required packages
'''
bash
$ pip install -r requirements.txt
'''

### Setup the enviroment variables

'''
$cp .env.example .env

'''
set your environment variable in the '.env' file. like
"OPEN_API_KEY"value

## Run the FastAPI server
'''
bash
$ uvicorn main:app --reload --host 0.0.0.0 -
-port 5000
'''

## postMan Collection
download POSTMAN collection from [\assets\mini-rag-app.postman_collection.json](\assets\mini-rag-app.postman_collection.json)