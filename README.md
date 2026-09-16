# rag-tutorial-v2 - Ollama version

Installing:
```
pip install -r requirements.txt
ollama pull nomic-embed-text
ollama pull mistral
```

Create/Update database:
```
python populate_database.py
```

Run query:
```
python query_data.py "How many dices there are in monopoly"
```



Original project: https://github.com/pixegami/rag-tutorial-v2

