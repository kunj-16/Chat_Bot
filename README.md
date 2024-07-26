Overview:
This project aims to develop a chatbot that can interact with multiple PDFs uploaded in a natural and
coherent manner using a large language model (LLM) such as gemini-pro. The chatbot is capable of understanding 
and responding to various user queries, generating the summary, and responding to user-raised questions.

Installation Steps-

1. Clone the Repository
2. Set Up a Virtual Environment  
3. Activate the Virtual Environment
    myenv\Scripts\activate
4. Install Required Libraries
    pip install -r requirements.txt
5. Configure Environment Variables
    - Create a '.env' file in the  directory and add your Google API key:
    env
   GOOGLE_PRO_API_KEY="your_api_key_here"
    

Usage Instructions-

1. Run the Streamlit App
    streamlit run app.py
2. Interacting with the Chatbot
    - Upload a PDF file via the interface
    - Enter a query related to the PDF content and get the response.
    - 
Dependencies-

- 'streamlit'
- 'langchain'
- 'python-dotenv'
- 'google-generativeai'
- 'pypdf2'
- 'langchain-google-genai'
