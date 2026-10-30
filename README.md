# AI Chatbot Playground

Beginner-friendly examples for calling different AI chat models with
LangChain. The examples cover prompts, structured output, Hugging Face
endpoints, local models, and a simple Streamlit chatbot UI.

## Run the Streamlit chatbot

```bash
uv venv
source .venv/Scripts/activate
uv pip install -r requirements.txt
streamlit run UIChatBot.py
```

Copy your API keys from the project's `.env.example` before running an
example that uses an external model provider.
