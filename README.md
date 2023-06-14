# Reader with AI: Transform Your Documents into Conversations with chatGPT 

Did you know that chatGPT can engage in interactive conversations with your documents? In this Python workshop, you will discover how to make it possible. Forget about limitations - now you can chat and explore your documents in a whole new way.

## Introduction
With this short project, you will learn how to unleash the full potential of chatGPT and convert your documents into interactive conversations. No more boring readings or tedious searches - now you can directly ask questions to your documents and receive responses from chatGPT. To develop this application in less than 50 lines of code, we will need:

- ChatGPT API
- Streamlit
- PyPDF2
- LangChain

## How It Works
1. Divide the document into chunks.
2. Create embeddings for each text chunk.
3. Store the chunks and embeddings in a knowledge base.
4. Search for the most relevant chunks based on the user's question using the embeddings.
5. Pass the most relevant chunks along with the question to chatGPT, which generates the response.

## Installation of ReaderAi
Using ReaderAI is easy! Here are the steps:

1. Clone or download the repository to your local machine.
2. Install the required libraries by running the following command in your terminal:
   ```
   pip install -r requirements.txt
   ```
3. Run the application with the following command:
   ```
   streamlit run app.py
   ```
4. Get an API key from OpenAI.
5. Enjoy the magic.🦄

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

  
