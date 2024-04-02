# Groq + streamlit demo

This app presents a streamlit chatbot interface with GROQ as the LLM infrastructure

## Installation

Follow these steps to set up your environment and run the application.

### 1. Install Requirements

First, ensure that you have Python installed on your system. Then, install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

This command will install all necessary packages, including Streamlit and python-dotenv, which are listed in your `requirements.txt` file.

### 2. Create the .env File

You need to create a `.env` file in the root directory of your project to store your Groq API key securely. This file should not be tracked by version control (add `.env` to your `.gitignore` file).

In your `.env` file, add the following line:

```
GROQ_API_KEY=your_groq_api_key_here
```

Replace `your_groq_api_key_here` with your actual Groq API key.

### 3. How to Run Streamlit

With the environment set up and the `.env` file in place, you can now run your Streamlit application. Execute the following command in your terminal:

```bash
streamlit run your_app.py
```

Replace `your_app.py` with the path to your Streamlit application script. Streamlit will start the server, and you should see a URL in the terminal that you can visit in your web browser to interact with the application.
