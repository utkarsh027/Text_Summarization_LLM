# LangChain: Summarize Text From YouTube or Website

## Overview

This project is a Streamlit application that uses LangChain and Groq's language models to summarize text from YouTube videos or websites. By providing a YouTube or website URL, users can generate concise summaries of the content in 300 words.

## Features

- **Summarize YouTube Videos**: Extract and summarize content from YouTube video URLs.
- **Summarize Webpages**: Extract and summarize content from webpages.
- **User-Friendly Interface**: Built with Streamlit for an interactive and intuitive experience.

## Requirements

- Python 3.8 or higher.
- A valid Groq API Key.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate
3. **Install Dependencies**:
  ```bash
  pip install -r requirements.txt
```


## Usage
Run the Application:
```bash
streamlit run app.py
```

# Interact with the Application:
Enter your Groq API Key in the sidebar.
Input a YouTube video URL or a webpage URL in the text field.
Click the "Summarize the content from YT or Website" button to generate a summary.
View the summarized content displayed in the application.
# Key Components
Groq Language Model: Utilizes Gemma2-9b-It from Groq to generate high-quality summaries.

LangChain Prompts: Custom prompt templates for summarizing content effectively.

Document Loaders:

YoutubeLoader: Extracts content from YouTube videos.
UnstructuredURLLoader: Extracts content from webpages.
# Code Structure

app.py             # The main Streamlit application script.
requirements.txt   # Contains all required Python libraries.

# Example Workflow
- **Input a valid YouTube or webpage URL**.
- **Provide your Groq API Key**.
- **Click the button to fetch and summarize the content**.
- **Review the 300-word summary displayed in the application**.
# Error Handling
Validation:

- **Ensures the Groq API Key and URL inputs are valid**.
- **Displays an error if the URL is invalid or missing**.
# Exception Handling:

Catches exceptions and displays user-friendly error messages in the application.


