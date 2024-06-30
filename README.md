# Customized Chatbot with RAG, LangChain, and OpenAI

Customized Chatbot with Retrieval-Augmented Generation (RAG), LangChain, and OpenAI is an interactive command-line application designed to facilitate a Q&A session about a specific topic using the LangChain library and OpenAI's GPT-4 model. The chatbot uses RAG to provide contextually relevant responses based on a document dataset.

## Some capture of the chat result
![image](https://github.com/zosk62/customized_chatbot_rag_langchain_openai/assets/157859516/a7987668-3fa7-4cd1-a0c4-5d3dd9f975af)


![image](https://github.com/zosk62/customized_chatbot_rag_langchain_openai/assets/157859516/5bab6ce3-22c9-4edc-99b4-1ed030c21382)

## Features

🔍 **Interactive Chat Interface:**

- Engage in a continuous conversation with the AI assistant.
- Receive context-aware responses from the assistant, leveraging RAG.

🛠️ **Flexible and Easy to Use:**

- Simple command-line interface for interaction.
- Type "quit" to end the chat session.

## Programs, Tools, and Libraries Used

### Programs:

- **Python:** 🐍 The programming language used for developing the chatbot application.

### Libraries:

1. **LangChain:** 🔗 A library for building language model applications.
2. **OpenAI:** 🤖 Provides the GPT-4 model for generating fallback responses.
3. **Chroma:** 📚 A vector store for storing and retrieving document embeddings.
4. **PyPDFLoader:** 📄 Loads and splits PDF documents for processing.
5. **LangChain_Community:** 🌐 Provides additional document loading utilities.

## Setup and Usage

Set the OpenAI API key as an environment variable:

```python
import os
os.environ["OPENAI_API_KEY"] = "sk-"
