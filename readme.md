<h1>Chat with a Website from URL - LangChain Chatbot with Streamlit GUI</h1>

Welcome to the GitHub repository for the LangChain Chatbot with Streamlit GUI! This project is a comprehensive guide to building a chatbot capable of interacting with websites, extracting information, and communicating in a user-friendly manner. It leverages the power of LangChain 0.1.0 and integrates it with a Streamlit GUI for an enhanced user experience.



<h1>Features</h1>
<li>Website Interaction**: The chatbot uses the latest version of LangChain to interact with and extract information from various websites.</li>
<li>Large Language Model Integration**: Compatibility with models like GPT-4, Mistral, Llama2, and ollama. In this code I am using GPT-4, but you can change it to any other model.</li>
<li>Streamlit GUI**: A clean and intuitive user interface built with Streamlit, making it accessible for users with varying levels of technical expertise.</li>
<li>Python-based**: Entirely coded in Python.</li>

<h1>Brief explanation of how RAG works</h1>

A RAG bot is short for Retrieval-Augmented Generation. This means that we are going to "augment" the knowledge of our LLM with new information that we are going to pass in our prompt. We first vectorize all the text that we want to use as "augmented knowledge" and then look through the vectorized text to find the most similar text to our prompt. We then pass this text to our LLM as a prefix.
![IMG20230609194730-Photoroom png-Photoroom](https://github.com/ajoshi222/chat-with-websites/assets/69758727/0692a7ca-2704-4605-a0bc-77235ae7f062)

 
 

![HTML-rag-diagram](https://github.com/ajoshi222/chat-with-websites/assets/69758727/c7fcb12d-3101-4ed2-bb09-76ef90f7f27e)

<h1>Installation</h1>
Ensure you have Python installed on your system. Then clone this repository:

```bash
git clone [repository-link]
cd [repository-directory]
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Create your own .env file with the following variables:

```bash
OPENAI_API_KEY=[your-openai-api-key]
```

<h1>Usage</h1>
To run the Streamlit app:

```bash
streamlit run app.py
```

 
---<h1>  c h a t - w i t h - w e b s i t e s </h1>
 
 
