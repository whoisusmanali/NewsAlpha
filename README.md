# NewAlpha: Stock News Extrator

NewAlpha is a web application built using Streamlit that summarizes news articles related to stocks. It utilizes LangChain's UnstructuredURLLoader to fetch data from websites, then employs RecursiveCharacterTextSplitter to split the text into segments for analysis. The text segments are embedded into vectors using OpenAIEmbeddings and stored in a FAISS database for efficient retrieval.

## Features

- Summarizes news articles related to stocks.
- Provides important details without the need to read the entire article.
- Utilizes LangChain's UnstructuredURLLoader for fetching data from websites.
- Employs RecursiveCharacterTextSplitter for segmenting the text.
- Embeds text segments into vectors using OpenAIEmbeddings.
- Stores embedded vectors in a FAISS database for efficient retrieval.
- Loads OpenAI's LLM model for question answering based on the provided text.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your_username/newalpha.git
```
2. Install dependencies:
``` bash
cd newalpha
pip install -r requirements.txt
```

## Usage
Run the Streamlit app:
``` bash
streamlit run app.py
```

Access the application via the provided URL.<br />
- Enter the URL of the news article you want to summarize.<br />
- Wait for the summarization process to complete.<br />
- View the summarized content and important details regarding the stocks mentioned in the article.<br />

## Dependencies <br />
- Streamlit: for building the web application.<br />
- LangChain: for fetching data from websites and text processing.<br />
- OpenAI: for text embeddings and question answering capabilities.<br />
- FAISS: for efficient vector storage and retrieval.<br />
