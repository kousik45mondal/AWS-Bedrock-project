# AWS-Bedrock

# AWS-Bedrock

store in data folder one document pdf 

using this pdf details we will be ask question and llama will give answer from related documents pdf context

# first step 
create iam user admin access and store all token

1. command -->
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip setuptools wheel
pip install -r requirements.txt

3. command -->
pip install -U langchain-aws langchain-community langchain-core langchain-classic


deployed in local using streamlit 
#command --> streamlit run app.py
