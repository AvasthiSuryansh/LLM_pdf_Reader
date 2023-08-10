# LLM_pdf_Reader
This project creates a LLM model that can be trained on a pdf. It can utilize either any hugging face model or openAI GPT3 APIs.
Chat with Multiple PDFs
This repository contains a Streamlit application that allows users to chat with multiple PDF documents. Users can upload their PDFs, and the application will extract the text and allow users to ask questions about the content of the documents.

Features
PDF Text Extraction: Extracts text from multiple uploaded PDFs.
Text Chunking: Splits the extracted text into manageable chunks for processing.
Vector Store Creation: Converts text chunks into vectors for efficient retrieval.
Conversational Interface: Engages in a conversation with the user based on the content of the PDFs.
Dependencies
streamlit: For creating the web application interface.
dotenv: For loading environment variables.
PyPDF2: For reading and extracting text from PDFs.
langchain: A custom library for text processing, embeddings, vector storage, chat models, memory management, and conversational chains.
htmlTemplates: Contains HTML templates for styling the chat interface.
How to Run
Clone the repository:

bash
Copy code
git clone <repository-url>
cd <repository-directory>
Install the required packages:

bash
Copy code
pip install streamlit dotenv PyPDF2
Run the Streamlit application:

bash
Copy code
streamlit run <filename>.py
Open the provided link in your browser to access the application.

Usage
Upload your PDF documents using the file uploader in the sidebar.
Click on the "Process" button to extract and process the text from the PDFs.
Enter your question in the text input field and get a response based on the content of your documents.
Contributing
Feel free to fork this repository, make changes, and submit pull requests. Any contributions, whether it's improving the code, adding features, or fixing bugs, are always welcome!


