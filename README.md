# Constitution-of-India-RAG-Chatbot

![Lion](https://github.com/user-attachments/assets/7c257cea-ccfb-4cb6-9e9e-88d6ab486b8b)

This repository contains a **Retrieval-Augmented Generation (RAG) chatbot** designed to answer questions related to the movie *Constitution Of India*. The chatbot was developed using **Langflow**, a tool for designing and deploying language models.

## Features

- **RAG Architecture**: Combines retrieval-based techniques with generative models to provide accurate and context-aware responses.
- **Specialized Knowledge**: Focuses exclusively on the world of *Constitution of India* Structure, Sections, themes, and closer details.
- **Langflow Integration**: Built using the visual interface of Langflow, which makes model design and customization seamless.


![3](https://github.com/user-attachments/assets/02fa7a2c-32d8-4a64-b4d0-31d291bfbc8f)


![1](https://github.com/user-attachments/assets/0eac53a5-a049-462c-9c31-e6b7614e1040)

![2](https://github.com/user-attachments/assets/7937652b-7d46-43b4-8f98-3ae8dfada074)



## How It Works

The chatbot leverages a **retriever** to search through a document base for relevant passages about *Constitution of India* and uses a **generator** to form coherent, natural-sounding responses.

### Key Components

1. **Retriever**: Extracts relevant information from the knowledge base, which contains detailed data about the Constitution.
2. **Generator**: Constructs a human-like response based on the retrieved information.

## Setup Instructions

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/swaraj-khan/Constitution-of-India-RAG-Chatbot.git
    ```


2. **Langflow Configuration**:
    The chatbot configuration has been built using Langflow, and the flow configuration is saved as a JSON file in this repository. You can load this file into Langflow by following these steps:
    
    - Open Langflow and click on **Upload Flow**.
    - Select the `Constitution-of-India-RAG-Chatbot.json` file.
    - Once uploaded, click **Run** to start the chatbot.

3. **Run the Chatbot**:
    After loading the flow in Langflow, you can start querying the chatbot directly through the interface. It will retrieve relevant information and generate answers related to *Constitution Of India*.



## Customization

You can modify the RAG model by adding more documents or training it on a larger corpus of *Constitution of India*-related data. The JSON file included can also be edited to adjust the pipeline's architecture.

## Contact

For any questions or suggestions, please reach out to [swarajkhan2003@gmail.com].
