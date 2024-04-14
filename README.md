Custom Chatbot using Langchain and Hugging Face Model

This is a custom chatbot project! This chatbot utilizes Langchain for language processing and a Hugging Face model for conversation generation.

Installation

To get started, follow these steps:

1. Clone the repository:
    git clone https://github.com/ManishaJohnson/customChatbot.git

2. Install the required Python packages:
    pip install -r requirements.txt

Usage

Once you have the project set up, follow these steps:

1. Add your files to the "data" folder.
   
2. Run the following command to ingest the data:
    ```
    python ingest.py
    ```

3. Check if the "vectorstores" folder is created.

4. Finally, run the chatbot model using the following command:
    ```
    chainlit run model.py -w
    ```

Before running the model, download the LLM (Llama Language Model) from the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGUF

Download the following version: llama-2-7b-chat.Q8_0.gguf

If you pick any other model, ensure to replace the model name in the code inside model.py.

Contributing
References:
Credits and huge thanks

1 https://www.youtube.com/watch?v=kXuHxI5ZcG0&t=379s

2 https://huggingface.co/TheBloke?search_models=llama-2-7B-
