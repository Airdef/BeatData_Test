# BeatData Interview Test Solution
This repository contains my solutions to the interview test. The code has been developed and tested within Google Colab and is meant to be used within that environment. Below, you will find details on how to set up and review my solution.

## Author
- **Name:** Filippo Andrea La Fauci
- **LinkedIn:** www.linkedin.com/in/filippo-la-fauci-eng

### Description
The model is configured to answer questions based on the specific knowledge space of the uploaded PDF. However, users can modify the code to enable the model to generalize responses, allowing it to correctly answer questions in contexts different from the original knowledge space. This generalization can be achieved using techniques such as deploying multiple agents or crafting custom prompts.

- model: gpt-3.5-turbo
- embeddings: text-embedding-3-small
- Python version: 3.10.12


## Clarifications

### Why Google Colab?
- I chose Google Colab as the platform for this project to ensure that anyone evaluating my submission could easily access and execute the code without needing any specific setup or environment configuration.
- ### Security Measures for API Key
- The application is designed to prompt for the key at runtime rather than storing it statically for security.
## Requirements
- Google Colab: The code is intended to be executed in a Google Colab environment.
- OpenAI API Key: You will need an API key from OpenAI to interact with their models.
- PDF Document: A PDF file that serves as the knowledge base for the application.
### Optimized for the Knowledge Base
- Reading instructions, I determined that focusing on the knowledge base would be the most appropriate approach.
### Exit After Five Unsuccessful Queries
- To prevent unnecessary processing, the application is designed to exit after five consecutive unsuccessful queries. 

### Why Google Colab?

## Getting Started

### Setting Up Your Environment

1. **Open Google Colab:**
   - Visit [Google Colab](https://colab.research.google.com) and sign in with your Google account.

2. **Clone the Repository:**
   - Open a new notebook and clone this repository by running the following command in a Colab cell:
     ```python
        !git clone https://github.com/yourusername/your-repository-name.git
     ```
  
3. **Open the Notebook:**
   - Navigate to the `your-repository-name` folder in the Colab file explorer, and open the notebook.
  
### Configuring Your OpenAI API Key

- Obtain an API key from [OpenAI](https://openai.com/):
  - Sign up or log in to your OpenAI account.
  - Navigate to the API section and generate a new API key.

- Once you have your API key, enter it when prompted by the notebook in Google Colab. This key is used to authenticate your requests to the OpenAI API.

### Uploading Your PDF Knowledge Base

- When the Colab notebook prompts you to upload a PDF, use the file upload feature in Colab to select and upload your PDF document from your local machine to the specified directory.

## Usage

Please follow the instructions within the notebook to:
- Input your OpenAI API key
- Input the PDF
- Ask question to the llm

