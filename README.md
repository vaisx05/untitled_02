# shaDocTalk

---

## Introduction to shaDocTalk

Welcome to **shaDocTalk**, an interactive PDF query application powered by OpenAI's GPT-3 and built using Streamlit. This project enables you to upload PDF files and ask natural language questions about their contents, receiving intelligent responses generated by OpenAI's language model.

### Key Features

- **PDF Upload**: Easily upload PDF files directly to the application.
- **Natural Language Processing**: Utilizes OpenAI's GPT-3 for advanced natural language understanding and response generation.
- **Query History**: Keeps track of your previous queries and responses for easy reference.
- **Customizable**: Adapt the application to fit specific use cases or integrate additional functionalities as needed.

### How It Works

1. **Upload PDF**: Drag and drop your PDF file into the application.
2. **Ask Questions**: Input questions about the uploaded PDF's content into the text box.
3. **Receive Answers**: shaDocTalk uses OpenAI's powerful GPT-3 model to process your queries and provide accurate answers.
4. **Explore History**: Review past queries and responses conveniently stored within the application.

### Why Use shaDocTalk?

shaDocTalk simplifies the process of extracting information from PDF documents using advanced natural language processing capabilities. Whether for research, document analysis, or educational purposes, shaDocTalk provides a seamless and intuitive interface for interacting with PDF content.


### Generating OpenAI API Key using OpenAI Playground

Follow these steps to generate an API key from OpenAI Playground:

1. **Visit OpenAI Playground**: Go to [OpenAI Playground](https://platform.openai.com/playground) using your web browser.

2. **Sign In or Sign Up**: If you already have an account, sign in using your credentials. If not, you can sign up for a new account by following the registration process.

3. **Access API Settings**:
   - Once logged in, navigate to the API section or settings. This can usually be found in the user profile or account settings menu.

4. **Generate API Key**:
   - Look for an option to generate an API key. It may be labeled as "Generate API Key" or similar.
   - Click on the button to generate a new API key.

5. **Copy API Key**:
   - After generating the API key, it will be displayed on the screen.
   - Copy the API key to your clipboard. Treat this key like a password and keep it secure.

6. **Use API Key**:
   - In your development environment, create or update a `.env` file (if not already created) in your project directory.
   - Add the API key in the `.env` file using the following format:

     ```
     OPENAI_API_KEY=your_generated_api_key_here
     ```

   - Replace `your_generated_api_key_here` with the API key you copied from the OpenAI Playground.

7. **Save and Secure**:
   - Save the changes to your `.env` file.
   - Ensure that the `.env` file is included in your project's `.gitignore` file to keep your API key confidential and secure.

By following these steps, you can successfully generate an API key from the OpenAI Playground and integrate it into your project for accessing OpenAI's services, such as using GPT-3 for natural language processing tasks. Remember to handle API keys securely and avoid sharing them publicly to maintain the security of your applications.

---

