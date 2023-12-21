# End-to-End-Medical-Chatbot-using-Llama2


# How to Run ?

Clone the Repo 

## Step 1 - Create a virtual env
`conda create -p mchatbot python=3.8 -y`

## Step 2 - Activate the virtual env
`conda activate mchatbot`

## Step 3 - Install the Requirements
`pip install -r requirements`

## Step 4 - Create a .env file in the root directory and add your Pinecone credentials as follows

`PINECONE_API_KEY = "********-****-****-****-************`

`PINECONE_API_ENV = "********-****-****-****-************"`

## Step 5 - Download the quantize model from the link provided in model folder & keep in the directory

`https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main`

## Download the Model - `Llama-2-7B-Chat-GGML/llama-2-7b-chat.ggmlv3.q4_0.bin`