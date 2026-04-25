# mini-rag

This is a minimal implementation of the RAG model for question answering.

## Requirments 

-Python 3.9 or latest

#### Install Python using MiniConda

1) Download and install MiniConda from [here](https://docs.anaconda.com/free/miniconda/#quick-command-line-install)

2) Create enviroment using the following command:
```bash
$ conda create -n mini-rag python=3.9
```

3) Activate the enviroment:
```bash
$ conda avtivate mini-rag
```

### (Optional) setup your cmmand line for better readability
```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```

## Installation

### Install the required packages

```bash
$ pip install -r requirementes.txt
```

### Setup the environment variables

```bash
$ cb .env.example .env
```

Set your environment variable in the `.env` file. Like `OPEN_API_KEY` value.

## Run the FastAPI server

```bash
 $ uvicorn main:app --reload --host 0.0.0.0 --port 5000
 ```
## POSTMAN collection

Download the POSTMAN collection from [/assets/mini-rag-app-postman_collection.json](/assets/mini-rag-app.postman_collection.json)