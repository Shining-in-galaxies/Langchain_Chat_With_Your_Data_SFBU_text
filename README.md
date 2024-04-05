# Langchain Chat With Your Data SFBU

**Langchain_Chat_With_Your_Data_SFBU_text** is a sophisticated Jupyter Notebook designed to demonstrate the integration of LangChain with OpenAI's API, enabling the development of a stateful, retrieval-augmented chat application. This project showcases how to dynamically interact with structured and unstructured data through conversational AI, combining the power of large language models (LLMs) with state-of-the-art retrieval techniques for enhanced query answering.

## Overview

The notebook takes you through the steps of setting up your environment, selecting the appropriate language model based on the current date, and initializing a conversation with OpenAI's ChatGPT model at zero temperature for deterministic outputs. It further demonstrates how to process large texts, utilize vector stores for efficient data retrieval, and manage a conversational state across multiple interactions.

### Process Explanation

1. **Environment Setup and LLM Selection:** Initially, the notebook sets up the necessary environment variables and selects an LLM based on the execution date, ensuring that the most current model is used for generating responses.

2. **Initialization of ChatOpenAI:** Utilizes OpenAI's API to start a chat session, setting the stage for a controlled, coherent conversation based on the chosen language model.

3. **Document Processing and Vector Store Utilization:** Demonstrates how to load, split, and process large documents using a custom text splitter. It then shows how these processed texts are embedded into a vector space using OpenAI's embeddings and stored in Chroma, a vector store, for efficient retrieval.

4. **Retrieval-Augmented Conversation:** Outlines the creation of a retrieval-augmented generation (RAG) chain that leverages both the language model for generating responses and the vector store for pulling in relevant document segments to answer queries.

5. **Stateful Chat History Management:** Explains how to maintain a conversation's state, allowing the system to provide context-aware responses that consider the entirety of the interaction history.

6. **Executing Conversational Queries:** Finally, it showcases how to execute queries against this setup, demonstrating the retrieval and conversation capabilities in action.

## Getting Started

To explore this project, clone the repository and open the `.ipynb` file in Jupyter Notebook or JupyterLab. Ensure you have Jupyter installed and that you've set up your environment according to the prerequisites outlined in the notebook.

## Acknowledgments

- Thanks to LangChain for the foundational tools and libraries that make projects like this possible.
- OpenAI for providing the powerful API and language models that drive the conversational AI components.
