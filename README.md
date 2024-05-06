# 🦜 langchain-rag-demo 🐑
Playground example from pixegami on rag

recommend creating a clean python virtual environment
I use `pyenv` but any other tool can be used `pipx`

## Setup
```
# pyenv
pyenv virtualenv 3.10 rag-venv
pyenv activate rag-venv

# openai api key .env file
OPENAI_API_KEY=<YOUR OPENAI KEY>

# install deps
pip install -r requirements.txt

# create the db
python create_database.py

# run query
python query_data.py "How does Alice meet the Mad Hatter?"



#
