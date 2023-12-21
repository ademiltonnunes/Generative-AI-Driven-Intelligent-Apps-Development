# SFBU Customer Support System - Chatbot From Files
## Overview
This project aims to implement a web application of a customer support system for SFBU that answers customer’s questions based in a loading PDF.
The system was designed as a Flask web application with HTML and CSS user interface. This project will use the ChatGPT OpenAI GPT-3.5 Turbo model.
Please, read the pdf file CS589_week6_q5_19679_AdemiltonMarcelo_DaCruzNunes.pdf. It will have all steps taken to develop this project.

## Implementation Steps

To run this application, follow these implementation steps:

### 1. Create a Virtual Environment

```bash
python3 -m venv venv bash
```

### 2. Activate the virtual environment:
```bash
. venv/bin/activate
```

### 3.Install the required Python packages:
```bash
pip install python-dotenv flask openai langchain pydantic==1.10.9 yt_dlp pydub pypdf bs4 tiktoken langchain[docarray] chromadb


```

### 4.Start the Flask application:
```bash
flask run
```
