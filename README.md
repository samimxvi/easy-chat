## EasyChat

EasyChat is a simple AI chatbot built with **Python, Streamlit, and OpenAI**. It provides a clean chat interface with conversation memory and customizable AI behavior.

## Features

* Interactive chat interface
* Conversation memory
* Select AI model
* Adjust AI creativity
* Customize the AI personality
* Start a new conversation
* Clear chat history
* API key stored securely using environment variables

## Technologies

* Python
* Streamlit
* OpenAI API
* python-dotenv

## Installation

### 1. Clone the project

```bash
git clone <your-repository-url>
cd NexaChat
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure your API key

Create a `.env` file:

```env
OPENAI_API_KEY=your-api-key-here
```

**Do not share your API key or commit the `.env` file to GitHub.**

### 4. Run NexaChat

```bash
streamlit run app.py
```

The application will open in your browser.
