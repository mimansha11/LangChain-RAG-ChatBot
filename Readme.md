LangChain-RAG-Streamlit-ChatBot

1. Install the Requirements :

       *pip install -r requirements.txt

2. Git Clone the Repository:

       git clone https://github.com/mimansha11/LangChain-RAG-ChatBot

3. you need to specify an OPENAI_API_KEY in an .env and api/chroma_utils.py file

   Example of .env key 

       OPENAI-API-KEY = <Openai-api-key>

4. Specify Langchain api key in .env file 

       LANGCHAIN-API-KEY = <lANGCHAIN-API-KEY>

5  Start the Backend Server:

      uvicorn main:app --reload

7. Start Frontend Server:

       streamlit run streamlit_app.py

worked with github.com/vineetvedant

LEARN MORE 

8. To Learn About LangChain , take a look at the following resources:

   https://python.langchain.com/docs/introduction/ - Learn About LangChain

9. To Learn About Streamlit : 

   https://docs.streamlit.io/ - Learn About Streamlit.
