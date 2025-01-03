# RAG Chabot using Taipy

**intelligent chatbot that combines Retrieval-Augmented Generation (RAG) principles with powerful tools like Taipy, LangChain, and Google's Gemini LLM. The chatbot will enable real-time querying of a StackUp FAQ dataset, providing precise and contextual responses.**

```bash
python3 -m venv .venv
```


*On macOS/ Linux:*
```bash
source .venv/bin/activate
```

*On Windows:*
```bash
.venv\Scripts\activate
```

*installing dependencies*

```bash
pip install -r requirements.txt
```

*add .env*

```bash
GOOGLE_API_KEY= your_api_key
```

get it from here[https://aistudio.google.com/apikey] 


*finally run it with*

```bash
taipy run main.py --use-reloader
```
