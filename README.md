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


