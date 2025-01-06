# chat-pdf-ollama-
chat with your pdf by ollama and llama3.2



pdf sample
https://samples-files.com/




ollama pull mistral

in app.py

llama3.2
to
mistral

@st.cache_resource
def initialize_llm():
initialized_llm = Ollama(model="mistral", request_timeout=6000)
return initialized_llm
