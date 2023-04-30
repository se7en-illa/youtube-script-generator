# **AutoGPT Youtube Video Script Generator**

<p>
This repository contains the source code for the AutoGPT Youtube Script Generator, a web application that uses Streamlit to generate film scripts automatically. The app is built on top of several technologies, including LangChain, OpenAI, Wikipedia, ChromaDB, and TikToken.
</p>

## **Installation**

To run the AutoGPT Youtube Script Generator on your local machine, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies by running
   ```
   pip install -r requirements.txt
   ```
3. Set up your OpenAI API key by creating a new file called **.env** in the root directory of the project and adding your API key as follows:
   ```
   OPENAI_API_KEY=<your_api_key>
   ```
4. Start the application by running
   ```
   streamlit run app.py
   ```
5. Once the application is running, you can access it by opening a web browser and navigating to the localhost provided in the terminal.

## **Technologies Used**

Here is an overview of the technologies used in this project:

- **Streamlit:** A web application framework used to build the user interface for the AutoGPT Film Script Generator.

- **LangChain:** A workflow management tool used to manage the workflow of the LLM (Large Language Model) pipeline.

- **OpenAI:** A natural language processing platform used to power the LLM pipeline and generate the film scripts.

- **Wikipedia:** An online encyclopedia used to connect OpenAI's GPT (Generative Pre-trained Transformer) model to a vast corpus of human knowledge.

- **ChromaDB:** A vector storage system used to store and retrieve the vector representations of the script data.

- **TikToken:** A backend tokenizer used to tokenize the input data for the GPT model.
