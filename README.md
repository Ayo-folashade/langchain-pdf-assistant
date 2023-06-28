# AI-Powered Virtual Assistant
The AI-Powered Virtual Assistant is a Streamlit-based application that utilizes OpenAI's language model, LangChain, and document retrieval techniques to provide information and answer questions related to uploaded PDF documents. It aims to assist users by analyzing the uploaded documents and generating relevant responses based on the content.

## Usage
- Install the required dependencies, including `Streamlit` and `LangChain`.
- Set up the `OpenAI API key` by creating a `.env` file in the project directory and adding the API key.
- Run the Streamlit app using the `streamlit run app.py` command.
- Upload a PDF document using the `"Upload Your PDF Document"` button.
- Enter a question related to the document in the text input field.
- Click the `"Enter"` button to submit the question.
- The virtual assistant will process the question and provide an answer based on the content of the uploaded document.

## Limitations
- The virtual assistant is designed to answer questions specifically related to your uploaded document. Asking unrelated questions may yield inaccurate or irrelevant answers.
- The accuracy of the answers depends on the quality and relevance of the uploaded document.
- The performance of the virtual assistant may vary depending on the complexity and length of the document.

## License
This project is licensed under the `MIT LICENSE`.
