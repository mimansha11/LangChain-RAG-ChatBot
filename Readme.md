                            LangChain-RAG-Streamlit-ChatBot

Install the Requirements :

*pip install -r requirements.txt

Git Clone the Repository:

git clone https://github.com/mimansha11/LangChain-RAG-ChatBot

you need to specify an OPENAI_API_KEY in an .env and api/chroma_utils.py file

Example of .env key 

OPENAI-API-KEY = <Openai-api-key>

Specify Langchain api key in .env file 

LANGCHAIN-API-KEY = <lANGCHAIN-API-KEY>

Start the Backend Server:

uvicorn main:app --reload

Start Frontend Server:

streamlit run streamlit_app.py



LEARN MORE 

To Learn About LangChain , take a look at the following resources:

https://python.langchain.com/docs/introduction/ - Learn About LangChain

To Learn About Streamlit : 

https://docs.streamlit.io/ - Learn About Streamlit.
