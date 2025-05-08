# Cold-Email-Generator-Using-GenAI-and-Llama-3.1

Generate personalized cold emails from job postings using LLMs, vector search, and automation.

**Features:**

- Extracts roles, skills, and requirements from job descriptions using Llama 3.1 via Groq API.

- Retrieves matching portfolio links using ChromaDB (vector similarity search).

- Generates cold emails tailored to each job post.

- (Optional) User interface with Streamlit for easy use.

## Tech Stack
| Component     | Tool/Library                              |
| ------------- | ----------------------------------------- |
| LLM           | Llama 3.1 (via Groq API)                  |
| Framework     | LangChain                                 |
| Vector Store  | ChromaDB                                  |
| Embeddings    | SentenceTransformers (`all-MiniLM-L6-v2`) |
| Frontend (UI) | Streamlit (optional)                      |
| Deployment    | Groq, Streamlit Cloud (optional)          |


## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
   

