# A simple RAG example

It takes a Google drive folder (`SOURCE_FOLDER_ID`), creates the embeddings for all documents and stores them in a local FAISS DB.

The final Streamlit application uses that index from a LangChain `ConversationalRetrievalChain` to enrich the LLM context.

Requires an `OPENAI_API_KEY` to be present. 

# 3rd Party APIs used

## OpenAI

https://platform.openai.com/

## Google APIs

https://console.cloud.google.com/apis


# Usage

```
conda activate langchain
```

TODO: Supply a requiremens.txt and drop the custom conda env.

## Creating new embeddings

```
python embeddings.py
```

## Run the application
```
streamlit run query.py
```


