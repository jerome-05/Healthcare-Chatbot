# Healthcare Chatbot using DistilBERT and SerpAPI

This project implements a Healthcare Chatbot that answers health-related questions by fetching context from the web using SerpAPI and applying a pre-trained DistilBERT question-answering model. 
The chatbot is deployed using Gradio for an interactive user interface.


## Features


**Question-Answering Model:** Uses distilbert-base-uncased-distilled-squad from Hugging Face's Transformers library.

**Context Retrieval:** Fetches relevant context from the web using SerpAPI.

**Interactive Interface:** Built with Gradio for ease of use.

**Applications:** Provides quick healthcare-related answers, helping users with basic information needs.


## Requirements


transformers

gradio

requests

serpapi


## Installation


**1. Clone the repository:**

```bash
git clone https://github.com/your-repo/healthcare-chatbot.git
cd healthcare-chatbot
```

**2. Install the required libraries:**

```bash
pip install transformers gradio serpapi requests
```


## Usage


**1. Set up your SerpAPI key:**
Sign up at SerpAPI to get an API key.

**2.Replace the placeholder API key in the code with your actual key:**

```bash
api_key = "your_serpapi_key_here"
```

**3.Run the chatbot:** Execute the script to start the Gradio interface:

```bash
python AI_PROJ.py
```

**4.Interact with the chatbot:**

Enter healthcare-related questions in the text input.
The chatbot will fetch relevant context from the web and provide answers.
