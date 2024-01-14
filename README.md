# Sales-Consultant
A sales-consultant based on LangChain. 
The project includes four parts:
1. Generated sales QA by GPT-4 using "GPT-4 Sales Phrases Prompt.txt" and used CharacterTextSplitter to split into documents
2. Utilized Faiss and OpenAIEmbeddings to create vectorstore for storing and retrieval
3. Based on LangChain RetrievalQA, created a sales bot implementing RAG(Retrival Augmented Generation)
4. Implemented Gradio GUI

# Run
python sales_chatbot.py
