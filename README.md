# 🤖 Chat with PDF locally using Ollama + LangChain 🤖 
#### Original Project Idea by @Tony Kimpkemboi on Youtube

This project demonstrates an implemention of a local RAG (Retrieval Augmented Generation) that lets you chat with your PDF documents using Ollama and LangChain. For experimentation purposes, this project is tested in a Jupyter Notebook Environment. 

## ✨ Features ✨

- 🔒 Fully local processing - no data leaves your machine
- 📄 PDF processing with intelligent chunking
- 🧠 Multi-query retrieval for better context understanding
- 🎯 Advanced RAG implementation using LangChain
- 📓 Jupyter notebook for experimentation


## 🚀 Implementation 🚀
If you want to use this on your own local setup, you can either watch Tony's video, or follow these simple steps below:

1. You will need to create a virtual environment first on so python dependencies and libraries don't clash

```
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

2. Install the requirementss
```
pip install -r requirements.txt
```

3. Ensure you have the Ollama package installed
```
pip install ollama
```

4. Update to Ollama 0.4.1 to prevent TypeError issues
```
pip install --upgrade ollama==0.4.1
```

Note: The application will run slower on CPU-only systems, but it will still work effectively.

## 📝 License

This project is open source and available under the MIT License.

---
