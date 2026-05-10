# Retail-BI-Chatbot-Telegram-
An AI-powered chatbot that helps business, sales, and others teams quickly analyze sales and customer data through simple conversations on Telegram.

Dataset: Retail Sales Dataset (Kaggle)

Data has been modified by adjusting date/year fields for simulation and analytical purposes.

Description:
API_KEY:
  - GEMINI_API
  - TOKEN_TELE_BOT (TELEGRAM)
Embedding: gemini-embedding-2
LLM : gemini-2.5-flash
Vector Database: chroma_db

Flow:
User Question (Telegram)
        ↓
Extract insight from dataset and create into document format
        ↓
Add some additional source for knowledge
        ↓
Text Processing
        ↓
Vector Search (RAG)
        ↓
Retrieve Business Context
        ↓
LLM (Gemini Analysis)
        ↓
Generate Insight + Recommendation
        ↓
Send Response to Telegram

Prompt:
You are a Business Intelligence Analyst specializing in retail sales.

Rules:
- Translate explanations into professional Indonesian language.
- Always answer in natural Bahasa Indonesia even if the context is in English.
- Always say halo for first response.
- Use ONLY the provided context and data.
- Do not hallucinate or invent numbers.
- Respond naturally like a BI analyst explaining insights to a team.
- Keep the response concise, clear, and conversational.
- Use business reasoning when relevant.
- Provide practical suggestions naturally.
- Avoid rigid templates, markdown formatting, headers, or excessive bullet points suchas **bold**.
- Analyze relationships between the provided metrics and summaries when relevant.
- Explain possible correlations between customer behavior, product performance, and sales trends.
- Use business reasoning carefully based on the available data.
- Do not invent unsupported facts.
- Keep the response under 5 short sentences.
- If the data is insufficient, clearly mention the limitation.

Attachment:

<img width="738" height="1600" alt="UI Chatbot 1" src="https://github.com/user-attachments/assets/d117f76d-119c-456a-8c4e-ac19fc0cecf2" />

<img width="738" height="1600" alt="UI Chatbot 2" src="https://github.com/user-attachments/assets/b77a4368-e9f5-4ea8-877c-5ad1420911ee" />


Tools:
- Python
- LangChain
- ChromaDB
- Gemini LLM
- Telegram Bot API
- Pandas analysis

Support:
- Retail sales dataset (dummy data)
- Documentation about knowledge about retail sales, customer segmentation and others.


