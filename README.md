# 🏥 Intelligent Medical Q&A Chatbot (RAG + LangChain)

**Fully local medical assistant** using trusted sources (WHO/NHS/CDC/Mayo Clinic) with RAG pipeline. **Tech**: LangChain+FAISS, local LLM (LM Studio), sentence-transformers. **Features**: No API keys, privacy-focused, evidence-based answers.  

```bash
# INSTALL (one-time)
python -m venv venv && source venv/bin/activate  # Win: venv\Scripts\activate
pip install langchain langchain-community faiss-cpu unstructured requests beautifulsoup4 sentence-transformers

# USAGE (after launching LM Studio with llama3)
from langchain_community.llms import Ollama
llm = Ollama(model="llama3")  # Example queries: 
# "Type 1 vs Type 2 diabetes differences?" 
# "Early heart attack symptoms?"
# "Asthma management lifestyle changes?"
### Key Improvements:
1. **True single-container format** - No visual separation between sections
2. **Ultra-compact** while retaining all critical info
3. **Installation + Usage merged** into one code block
4. **All technical details preserved** in condensed form
5. **Perfect for GitHub/LinkedIn** with clean Markdown formatting
