# Document Research Tool  

A web application designed to process documents, extract meaningful information, and provide contextual question-answering capabilities.  

## Table of Contents  
- [Features](#features)  
- [Technology Stack](#technology-stack)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Demo](#demo)  
- [License](#license)  

## Features  
- Process URLs, PDFs, and HTML content.  
- Generate embeddings using OpenAI models.  
- Index and retrieve data efficiently with FAISS.  
- Answer questions with context and source attribution.  
- Progress tracking and user-friendly error handling.  

## Technology Stack  
- **Frontend Framework**: Streamlit  
- **Language Model**: OpenAI GPT  
- **Vector Database**: FAISS  
- **Document Processing**: LangChain  
- **Embeddings**: OpenAI Embeddings  

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/document-research-tool.git
   cd document-research-tool

## Requirements
pip install -r requirements.txt

## OpenAI API (.config)
OPENAI_API_KEY=your_openai_api_key

## Streamlit
streamlit run app.py


document-research-tool/
│
├── app.py              # Streamlit app to launch the web interface
├── requirements.txt    # Python dependencies for the project
├── .env                # Configuration for environment variables
├── README.md           # Project documentation (this file)
├── main.py             # Main source code
